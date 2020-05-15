# QR-Generator
----

URL to QR

## Get Started

1. `docker build -t qrgen ./`

1. `cat url.txt | docker run --rm -i --net=none qrgen qrencode -l L -o - > qr.png`
