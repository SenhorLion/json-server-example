#json-server example

json-server makes it extremely easy to setup robust JSON apis to use for demos and proof of concepts.

This example shows how to generate datasets using lodash and faker.

## Usage:

NB: You will need `json-server` installed: `npm install -g json-server`

1. Install dependencies:
   `npm install`

1. Generate db data:
   `json-server generate.js`

1. Run json server:
   `npm run db`

1. Then visit:
   http://localhost:3000 - json-server home
   http://localhost:3000/people - list of people generated

1. To use the json-server "externally" E.g: from device or another machine, you can run ngrok and use the forwarding address:
   `npm run tunnel`
