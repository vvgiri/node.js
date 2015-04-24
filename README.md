# Proxy Server
This is a Proxy Server for Node.js submitted as the [pre-work](http://courses.codepath.com/snippets/intro_to_nodejs/prework) requirement for CodePath.

Time Spent: [1 hr]

### Completed:
- [done] Required: Requests to port `8000` are echoed back with the same `HTTP` headers and body
- [done] Required: Requests/reponses are proxied to/from the destination server
- [done] Required: The destination server is configurable via the `--host`, `--port` or `--url` arguments
- [done] Required: The destination server is configurable via the `x-destination-url` header
- [done] Required: Client requests and respones are printed to stdout
- [done] Required: The `--logfile` argument outputs all logs to the file specified instead of stdout
- [todo] Optional: The `--exec` argument proxies stdin/stdout to/from the destination program
- [todo] Optional: The `--loglevel` argument sets the logging chattiness
- [todo] Optional: Supports HTTPS
- [todo] Optional: `-h` argument prints CLI API

### Recording of the prework in gif

### Steps for running the prework

```
//npm install first

nodemon --exec babel-node -- index.js --logFile=/Users/vgiri/proxy-server/proxy-server.log

curl -v -X POST http://127.0.0.1:8000 -H 'x-learnNode: Hurray' -d 'Hey Adam '

curl -v http://127.0.0.1:8001/canuselectme -d 'Hey Adam '

```

