# snacks-data
Data repository for the factsforfriends app

## Data model

Data is mainly stored in `data.json`. Every snack has the following attributes:

* unique ID (`ID`)
* a headline (`Headline`)
* the snack text (`Snack`)
* an alternative text that will be rendered into a sharepic (`Sharepic`)
* a URL for the fact-snack source (`URL`)
* a collection of words to be highlighted in the sharepic (`Highlight`)
* a whitespace-separated list of tags (`Tags`)
* a category (`Category`)
* a Location (`Location`)
* the medium, in which the fake news was spotted (`Medium`)

## License

The data is licensed under MIT. See also the file `LICENSE`.
