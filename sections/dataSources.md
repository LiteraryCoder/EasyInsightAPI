Data Sources
========

Get data sources
------------

* `GET /dataSources.json` will return all data sources available to the authenticated user.

Get data source
------------

* `GET /dataSources/1.json` will return details about the specified data source.

Add rows to data source
------------

* `POST /dataSources/1/rows.json` will add rows of data to the specified data source.

```json
{
  "rows": {
    "field1": 500,
    "field2": "Person",
    "field3": "2014-01-02'T'12:05:01"
  }
}
```

Replace rows in data source
------------

* `POST /dataSources/1/rows.json?action='replace'` will replace the data of the specified data source with the passed in rows.

```json
{
  "rows": {
    "field1": 500,
    "field2": "Person",
    "field3": "2014-01-02'T'12:05:01"
  }
}
```