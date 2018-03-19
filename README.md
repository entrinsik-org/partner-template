# partner-template

A simple proxy server that demonstrates how to embed Informer content. All requests for Informer content (`/informer/*`) are forwarded to the Informer application server.

# Getting started
1. Clone the repository
2. Make sure that Node v8 is installed
3. Run `npm install`
4. Start the server: `node index.js --port <port> --api.root http://<informer server>:<informer port> --api.auth <Basic ... | Token ...>`  The server will default to use basic auth for user/pw admin:123
