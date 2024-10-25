# Back-End Solution 

## Description

The application consists of a database (SQLite) and a Node.js REST API (Express).

----

## Tasks 
   
- [x] Endpoint: Get Available Countries:

    - Create an API endpoint, using Date Nager API `https://date.nager.at/api/v3/AvailableCountries`
    - This endpoint should return a list of    available      countries.

- [x] Endpoint: Get Country Info:

    - Create an API endpoint to retrieve detailed information about a specific country.
    - This endpoint should provide the following data:

        a. List of Border Countries: A list of countries that share a border with the selected country https://date.nager.at/api/v3/CountryInfo/UA.

        b. Population Data: Historical population data for the country, suitable for plotting on a chart https://countriesnow.space/api/v0.1/countries/population
    
        c. Flag URL: A URL to the country’s flag image https://countriesnow.space/api/v0.1/countries/flag/images





----
## How to run

- Make sure that you have node.js installed in your machine (version 16+)

### Install the dependencies

```bash

npm install

# or

yarn install

# or 

pnpm install # recomended

```


### Start the server in development mode

Get sure that the port `3333` is open.

If not, add a port number to the `PORT` environment variable (.env file).

```dotenv
PORT=3333 # Default value
```

```bash

npm run dev

# or

yarn dev

# or

pnpm dev # recomended

```

-----

### Start the server in production mode

```bash

npm run build

npm run start

# or

yarn build

yarn start

# or

pnpm build # recomended

pnpm start # recomended

```

### Access the api

[SWAGGER/DOCS](http://localhost:3333/api/v1/docs)

[API](http://localhost:3333/api/v1)


