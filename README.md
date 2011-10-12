# Configuration for using thttpd as a CGI processor for Nginx

## Introduction

This is a [thttpd](http://www.acme.com/software/thttpd/) configuration
for running the tiny HTTPD as a CGI processor upstream of
[Nginx](http://nginx.org).

## Features

 1. Bond to the loopback device: 127.0.0.1.
 
 2. Capability of running CGI scripts.
 
 3. Use of unpriveleged ports for both practical and security reasons.
 
## Usage

This configuration is used for
[relaunching](https://github.com/perusio/php-fpm-relaunch) php-fpm
when a 502 is captured by Nginx.
