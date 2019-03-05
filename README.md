#json-server example

json-server makes it extremely easy to setup robust JSON apis to use for demos and proof of concepts.

This example shows how to generate datasets using lodash and faker.

## Usage:

NB: You will need `json-server` installed: `npm install -g json-server`

1. Install dependencies:
   `npm install`

2. Generate db data:
   `json-server generate.js`

3. Then visit:
   http://localhost:3000 - json-server home
   http://localhost:3000/people - list of people generated
