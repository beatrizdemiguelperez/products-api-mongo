# products-api-mongo

a [Sails v1](https://sailsjs.com) application

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)

## Installation

* `git clone <repository-url>` this repository
* `cd products-api-mongo`
* `npm install`

Edit your [datastore config](config/datastores.js) to match your mongo url

## Running / Development

* `sails lift`
* Visit your app at [http://localhost:1337](http://localhost:1337)

### Building

* `sails lift --prod` (production)

## Further Reading / Useful Links

* [Sails.js](https://sailsjs.com)

### Api examples:

POST http://localhost:1337/user/login
body: {
  name: 'admin'
  password: 'admin'
}

POST http://localhost:1337/user/signup
body: {
  name: 'admin'
  password: 'admin'
  isAdmin: true
}

POST http://localhost:1337/product
body: {
  name: 'my super product'
  description: 'my super product description'
}

GET http://localhost:1337/product
