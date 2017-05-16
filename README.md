# DataViz-DojoKata

Demo example DataVIz - DojoKata

In this example we build an website with HTML+CSS+JS with charts and connect to a node-express backend to get the data.
This code it's intented to learn and generate from scratch, step by step.

1. Create index.html & show with [http-server](https://www.npmjs.com/package/http-server)
2. Add [Bootstrap](http://getbootstrap.com/)@3 & [JQuery](https://jquery.com/)@2 through a CDN like [cdnjs](https://cdnjs.com/)
3. Add [D3](https://d3js.org/)@3.3 & NVD3](http://nvd3.org/)@latest and generate an static chart
4. Add a second chart (pref. some with d3.json() => {} )
5. Create a node backend with [express](http://expressjs.com/)@4
6. Connect both to populate chart by an AJAX call

To run, you need:

One term for the frontend:

```shell

  # Install http-server (globally as tool)
  $ npm install -g http-server
  
  # Run the webserver (in the project folder)
  $ hs
  
  # Go to your browser: http://localhost:8080

```shell

Another term for the backend:

```shell
  
  # Install express (locally inside the project folder)
  $ npm install express
  
  # Run
  # node server.js

```shell


