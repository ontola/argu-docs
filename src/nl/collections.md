# Collecties (geavanceerd)

Collecties zijn lijsten van Items die je kunt sorteren, filteren en op verschillende manieren kan weergeven. Dit is een geavanceerde functionaliteit die je meestal niet nodig zal hebben, maar die wel erg krachtig kan zijn om je pagina precies zo te maken zoals jij dat wil. Als dit te ingewikkeld is, helpen we je uiteraard graag bij het instellen.

Je kunt een collectie openen door op de titel te klikken. Vervolgens kan je in de menu's rechts naast de titel bepaalde opties (zoals sorteren) eenvoudig zelf wijzigen. Wanneer je klikt op een optie, zal de link in je adresbalk wijzigen. In die link staan optionele _query parameters_. In de volgende link is een _display_ en en _type_ [query parameter](https://en.wikipedia.org/wiki/Query_string) meegegeven:

`https://argu.co/argu/help/discussions?display=grid&type=infinite`

Met deze query parameters kan je veel instellen over hoe een collectie zal verschijnen:

- **display** is weergave van de items. Mogelijke waarden zijn `grid` (losse kaarten in raster) of `table` (als rijen in een tabel).
- **sort** is op welke eigenschap er wordt gesorteerd. Moet een URL zijn van de eigenschap.
- **filter[]** is een key-value combinatie van een veld en zijn waarde
- **type** kan op **infinite**
- **title** veranderd de weergegeven naam van een collectie

Let er op dat waarden [URL encoded](https://www.urlencoder.org/) moeten worden meegegeven.

## Filters

Door een of meerdere `filter[]` parameters toe te voegen worden alleen items die overeenkomen getoond.

Om alleen de vraagstukken van een `discussions` collectie te tonen, moet het veld
`http://www.w3.org/1999/02/22-rdf-syntax-ns#type` en de waarde `https://argu.co/ns/core#Question` toegevoegd worden.

```JavaScript
const url = new URL('https://argu.nl/forum/discussions')
const field = encodeURIComponent('http://www.w3.org/1999/02/22-rdf-syntax-ns#type')
const value = encodeURIComponent('https://argu.co/ns/core#Question')
url.searchParams.append('filter[]', `${field}=${value}`)
url.toString()
```

Wat resulteerd in de volgende url:

```
https://argu.nl/forum/discussions?filter%5B%5D=http%253A%252F%252Fwww.w3.org%252F1999%252F02%252F22-rdf-syntax-ns%2523type%3Dhttps%253A%252F%252Fargu.co%252Fns%252Fcore%2523Question
```
