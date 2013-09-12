# Register hipache

This is a simple CLI app to register a domain in 
[Hipache](https://github.com/dotcloud/hipache).

I use this together with [Docker](http://docker.io) to register applications
into Hipache with a domain alias.

## Usage

    ./hipache-register -n wwwapp.example.com -b http://host.example.com:4567 -s host.example.com
    
Help:

    -n - Domain alias used for the app
    -b - Backend for the app
    -s - Server that exposes the Redis instance for hipache

Where wwwapp.example.com is the alias domain name to be used,
http://host.example.com:4567 is where the application is and host.example.com is
where the hipache redis instance lives.
