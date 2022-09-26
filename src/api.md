# API

All the information you see on Argu is communicated through the API. You can also reuse this API in other applications.

## Principles

- The API complies with [Linked Data / RDF](https://ontola.io/what-is-linked-data/) and [REST API guidelines](https://ontola.io/blog/api-design/). This goes further than REST APIs you may already know: with us, literally everything is a link, making the API navigable like a website. We therefore do not need any OpenAPI configuration.
- The URL of the page is also the identifier, and thus the API query point. In other words, every page you view is also an API endpoint.
- The API serialises to multiple RDF formats (JSON-LD, Turtle, N-Triples, RDF/XML and more) and uses [content negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation).
- All forms use [SHACL shapes](https://www.w3.org/TR/shacl/), which specifies the form that data must take to be valid.
- All actions are described as linked data, as [Schema Actions](https://schema.org/Action).
- Changes in data are communicated by means of [Linked-Deltas](https://github.com/ontola/linked-delta/).

## Getting started

The API works over HTTP. You can do that by using [curl](https://curl.haxx.se/) or [ldget](https://github.com/ontola/ldget/) in your terminal, or [fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) if you use Javascript. Search for ["HTTP &lt;programminglanguage&gt; library"](https://www.google.com/search?q=http+python+library) to find software to get you started.

Then you can fetch entities in the format you want with [HTTP content negotiation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Content_negotiation). In the HTTP Accept header, set the content type (such as 'application/empathy+json'):

```HTTP
GET https://argu.co/argu/help HTTP/1.1
Accept: application/empathy+json
```

The preferred type is `application/empathy+json`, but the following types are also possible:

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

You can also add one of the following extensions to the URL instead:

`.empjson` `.json` `.jsonld` `.n3` `.nt` `.nq` `.ttl` `.rdf`

Note that the extension goes directly after the path, before the query parameters and the fragment.

If you are going to use the data as RDF (linked data) and not as JSON, you will need to use an RDF parser. Read [more about RDF serialisation formats here](https://ontola.io/blog/rdf-serialization-formats/). Find an RDF library for your language and work with it.

## Report reuse

Have you created something with our API? Let us know about it!

## Changes

We do our best to keep the API as stable as possible. However, the API is subject to change as Argu is always evolving. Because we have no hard-coded endpoints, but do use persistent URLs as identifiers, changes would typically have minimal impact on re-users. However, please do get in touch if you need specific security for a longer period of time.

## Tokens

The API is publicly available. However, if you want to log in, write data or access closed data, you need a Token.

The Argu platform supports the [OpenID Connect](https://openid.net/connect/)
specification including the [dynamic client registration](https://openid.net/specs/openid-connect-registration-1_0.html)
extensions. Specifics on configuration can be requested on the `/.well-known/openid-configuration.json` endpoint.

## Data dumps / exports

See the article [Data Exports](export_data.md)

## Need help with the API?

Create an issue in the [GitLab issue tracker](https://gitlab.com/ontola/argu/-/issues)!
