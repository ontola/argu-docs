Alle informatie die je ziet op Argu, wordt middels de API gecommuniceerd. Deze API kan je ook zelf hergebruiken in andere applicaties.

## Principes

- De API voldoet aan [Linked Data / RDF](https://ontola.io/what-is-linked-data/) en [REST API richtlijnen](https://ontola.io/blog/api-design/). Dit gaat verder dan REST API's die je misschien al kent: bij ons is letterlijk alles een link, waardoor de API te navigeren is zoals een website dat ook is. We hebben hierdoor geen OpenAPI configuratie nodig.
- De URL van de pagina is tevens de identifier, en daarmee ook het API bevraagpunt. Met andere woorden, iedere pagina die je bekijkt, is tevens een API endpoint.
- De API serializeert naar meerdere RDF formaten (JSON-LD, Turtle, N-Triples, RDF/XML en meer) en maakt gebruik van [content negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation).
- Alle formulieren maken gebruik van [SHACL shapes](https://www.w3.org/TR/shacl/), waarin staat aan welke vorm data moet voldoen om valide te zijn.
- Alle acties zijn als linked data omschreven, als [Schema Actions](https://schema.org/Action).
- Wijzigingen in data worden gecommuniceerd door middel van [Linked-Delta's](https://github.com/ontola/linked-delta/).

## Aan de slag

De API werkt over HTTP. Dat kan middels [curl](https://curl.haxx.se/) of [ldget](https://github.com/ontola/ldget/) in je terminal, of [fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) als je Javascript gebruikt. Zoek naar ["HTTP &lt;programmeertaal&gt; library"](https://www.google.com/search?q=http+python+library) om software te vinden die je op weg helpt.

Vervolgens kan je entiteiten binnenhalen in het format dat jij wil met [HTTP content negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation). Zet in de HTTP Accept header het content-type (zoals 'application/empathy+json'):

```HTTP
GET https://argu.co/argu/argu/help HTTP/1.1
Accept: application/empathy+json
```

Het `application/empathy+json` type heeft de voorkeur, maar de volgende types zijn ook mogelijk:

```
application/empathy+json
application/json
application/ld+json
text/n3
application/n-triples
application/hex+x-ndjson
application/n-quads
text/turtle
```

Je kunt in plaats daarvan ook een van de volgende extensies achter de URL zetten:

`.empjson` `.json` `.jsonld` `.n3` `.nt` `.nq` `.ttl` `.rdf`

Let dat de extensie direct na het pad geplaatst moet worden, voor de query parameters en het fragment.

Als je de data als RDF (linked data) gaat gebruiken en niet in als JSON, zal je een RDF parser moeten gebruiken. Lees [hier meer over RDF serializatie formaten](https://ontola.io/blog/rdf-serialization-formats/). Zoek een RDF library voor jouw taal uit en ga er mee aan de slag.

## Hergebruik melden

Heb jij iets gemaakt met onze API? Laat het weten!

## Wijzigingen

We doen ons uiterste best om de API zo stabiel mogelijk te houden. De API is echter wel onderhevig aan veranderingen, aangezien Argu altijd in ontwikkeling is. Doordat we geen hard-coded endpoints hebben, maar wel persistente URLs gebruiken als identifiers, zouden wijzigingen doorgaans minimale impact hebben op hergebruikers. Neem echter wel contact op als je voor langere tijd een specifieke zekerheid nodig hebt.

## Tokens

De API is publiek beschikbaar. Als je echter wil inloggen, data wil schrijven of bij gesloten data wil komen, heb je een Token nodig.

Het Argu platform ondersteund de [OpenID Connect](https://openid.net/connect/)
specificatie inclusief [dynamic client registration](https://openid.net/specs/openid-connect-registration-1_0.html).
Details over de configuratie kunnen worden opgevraagd met het `/.well-known/openid-configuration.json` endpoint.

## Data dumps / exports

Zie het artikel [Data Exports](https://argu.co/argu/t/10808).

## Hulp nodig?

Stel hieronder je vraag, of mail direct naar [joep@argu.co](mailto:joep@argu.co).
