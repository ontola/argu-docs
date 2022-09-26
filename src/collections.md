# Collections (advanced)

Collections are lists of Items that you can sort, filter and display in different ways. This is an advanced functionality that you will usually not need, but it can be very powerful to make your page exactly the way you want it. If it's too complicated, we'll be happy to help you set it up.

You can open a collection by clicking on its title. Then you can easily change certain options (such as sorting) in the menus to the right of the title. When you click on an option, the link in your address bar will change. In that link are optional _query parameters_. In the following link, a _display_ and a _type_ [query parameter](https://en.wikipedia.org/wiki/Query_string) are provided:

`https://argu.co/argu/help/discussions?display=grid&type=infinite`

With these query parameters, you can set a lot about how a collection will appear:

- **display** is display of the items. Possible values are `grid` (individual cards in a grid) or `table` (as rows in a table).
- **sort** is on which property it will be sorted. Must be a URL of the property.
- **filter[]** is a key-value combination of a field and its value
- **type** can be set to `paginated` or `infinite`
- **title** changes the displayed name of a collection

Please note that values [URL encoded](https://www.urlencoder.org/) must be provided.

## Filters

Adding one or more `filter[]` parameters will only show items which match the given field and value comibnation.

For example, to only retrieve questions from a `discussions` collection, set the field to 
`http://www.w3.org/1999/02/22-rdf-syntax-ns#type` and the value to `https://argu.co/ns/core#Question`.

```JavaScript
const url = new URL('https://argu.nl/forum/discussions')
const field = encodeURIComponent('http://www.w3.org/1999/02/22-rdf-syntax-ns#type')
const value = encodeURIComponent('https://argu.co/ns/core#Question')
url.searchParams.append('filter[]', `${field}=${value}`)
url.toString()
```

Which will result in the following URL:

```
https://argu.nl/forum/discussions?filter%5B%5D=http%253A%252F%252Fwww.w3.org%252F1999%252F02%252F22-rdf-syntax-ns%2523type%3Dhttps%253A%252F%252Fargu.co%252Fns%252Fcore%2523Question
```
