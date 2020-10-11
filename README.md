# nginx
nginx configurations

## Installation

1. replace root configuration file
> cp nginx.conf /etc/nginx/nginx.conf

2. copy default configuration to configurations directory
> cp default.conf /etc/nginx/conf.d/default.conf

## Activation of configuration changes

1. test configuration
> nginx -t
> nginx -T

2. activate configuration
> nginx -s reload