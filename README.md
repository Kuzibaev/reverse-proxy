# A simple reverse proxy

We can see realserver in realServer and proxy server in reverseServer

Open `cd realServer` realServer and run `go run .` it.

Open `cd reverseServer` reverseServer and run `go run .` it.

Run this two file and if we do some request like `curl 'http://localhost:8002/:path`

we will get a response in JSON contains ip of client and path we requested.
