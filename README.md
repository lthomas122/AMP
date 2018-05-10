# PLP on AMP :zap:
A basic product list page that uses AMP, generated using simple content made from a Peerius JSON file.

### What you need to run it :floppy_disk:
You will need the following dependencies installed to run this project:
- **node/npm** for running localhost - [Download](https://nodejs.org/en/download/)
- **http-server** (install by running `npm install -g http-server`) [[Package URL](https://www.npmjs.com/package/http-server)]
- **json-server** (install by running `npm install -g json-server`) [[Package URL](https://www.npmjs.com/package/json-server)]

> **TIP:** You may want to update npm, http-server and json-server after installing them.

### How to get it running :running:
Please ensure you have installed aforementioned dependencies above before going any further.
1. Navigate to AMP project folder in cmd
2. Run `http-server`
3. Run `json-server --watch product.json`
4. Go to the [AMP file](hellworld.amp.html#L116) and change the `<amp-list>` src attribute on `line 116` to `//localhost:3000/productRecs` or whatever port you are running the database on `json-server`
5. Go to `localhost:8080` or whatever port you are running on the `http-server`
