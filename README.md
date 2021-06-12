# Node-resource-server

set-up

    $ npm install

Generate cert (for linux / mac)

    $ openssl req -x509 -newkey rsa:2048 -keyout tempkey.pem -out cert.pem -days 365

    $ openssl rsa -in tempkey.pem -out key.pem

Run server

    $ node index.js