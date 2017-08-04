Docker Compose - FreeGeoIp

This is the source code of the freegeoip software.
It contains both the web server that empowers freegeoip.net, and a package for the Go programming language that enables any web server to support IP geolocation with a simple and clean API.
https://github.com/fiorix/freegeoip

Run:

docker-compose up

Test:
http://localhost:8080/json/1.2.3.4

Or:
curl localhost:8080/json/1.2.3.4
