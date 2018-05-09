# PLP on AMP
A basic product list page that uses AMP, generated using simple content made from a Peerius JSON file.

### What you need to run it
You will need the following dependencies installed to run this project:
- node/npm for running localhost
- http-server (install by running `npm install -g http-server`)
- json-server (install by running `npm install -g json-server`)

### How to get it running
Please ensure you have installed aforementioned dependencies above before going any further.
1. Navigate to AMP project folder in cmd
2. Run `http-server`
3. Run `json-server --watch products.json`
4. Change the `<amp-list>` src on `line 116` to `//localhost:3000` or whatever port you are running the database on `json-server`
5. Go to `localhost:8080` or whatever port you are running the `http-server` on
