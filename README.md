# esp8266-https-ca-demo

A short example of how to use a CA-signed certificate on your HTTPS server with an ESP8266.

The main gotcha is that the clock must be set before calling `verifyCertChain`, otherwise verification will always fail.
