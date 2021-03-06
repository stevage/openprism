Type your search in one search bar, and get results from all of the Socrata and CKAN portals.

## Technical
This is a static website that calls the Socrata and CKAN APIs. Build like so.

```sh
npm install -g browserify
npm install
browserify src/index.js -o bundle.js
```

## References

Data portal search API documentation

* [Junar](http://wiki.junar.com/index.php/API)
* [Socrata](https://github.com/jasonlally/open-data-browser/blob/dev/data/dataportalapi.py)
* [CKAN](http://docs.ckan.org/en/ckan-1.7/apiv3.html)

## To do

* Add [OpenDataPhilly](http://opendataphilly.org/api-doc/)
    and [siblings](http://technical.ly/philly/2013/09/20/opendatacincy-launches/).
* Add [OpenEI](http://en.openei.org) with URLs like
    `http://en.openei.org/services/api/content_assist/recommend?topic=farms&callback=aoeu&version=1`
