# PostgreSQL Introspection

1. Install all npm packages with `npm install`.
2. Replace `env.process.PG_URI` in the `dbConnect.js` file with your own db URI.
3. Spin up the server with `npm start`.
4. Make a request to `http://localhost:3000/db/schemas` with your browser (or a tool like Postman), and view the basic schema data for your database. This data can then be used for other purposes, such as creating schemas for a GraphQL API.
