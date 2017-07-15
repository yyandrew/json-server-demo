# json-server demo
## the source code [json-server](https://github.com/typicode/json-server)

## how to start server
```
npm install json-server
cd json-server-demo
npm i
json-server --watch db.json --port 3001
```

## how to use

Open [http://localhost:3001](http://localhost:3001).

* Get single company

  Open [http://localhost:3001/companies/1](http://localhost:3001/companies/1)

* Get all users or companies

  Open [http://localhost:3001/companies](http://localhost:3001/companies)

  Open [http://localhost:3001/users](http://localhost:3001/users)

* Filter companies by name

  Open [http://localhost:3001/companies?name=Google](http://localhost:3001/companies?name=Google)

* Pagination & limit

  Open [http://localhost:3001/companies?_page=1&_limit=2](http://localhost:3001/companies?_page=1&_limit=2)

* Sorting

  Open [http://localhost:3001/companies?_sort=name&_order=asc](http://localhost:3001/companies?_sort=name&_order=asc)

* Full text search

  Open [http://localhost:3001/companies?q=software](http://localhost:3001/companies?q=software)


