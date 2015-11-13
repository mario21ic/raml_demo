npm install -g osprey-cli
osprey new api.raml --name test --target test
cd test && npm install
cd src && node app.js
