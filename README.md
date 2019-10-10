# TFTP
Simple implementation of a TFTP server (RFC1350) in C
## Usage
* Server

Compile and execute the server:

```
cd server
make
sudo ./tftps [directory]
```
This server was implemented using the guidelines of the
(RFC 1350)[https://tools.ietf.org/html/rfc1350].

## Pending tasks

* Send error packets (noted in the RFC as "only courtesy".)

* Implement (RFC 2348)[https://tools.ietf.org/html/rfc2348]
and maybe (RFC 7440)[https://tools.ietf.org/html/rfc7440].
