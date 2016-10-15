# webglueio

`webglueio` is a tool chain that scans your local development website and produces a build just like
our server on https://webdesignio.com would do.  You can use this to build your website in the rare
case that our service doesn't work.

## Install

    $ npm install -g @webdesignio/webglueio

## Usage

    $ cd mywebsite/
    $ webglueio

This produces a build directory `webfile-XXXXXX` in the website directory.  This can then be easily
deployed using your desired publishing tool (e.g. surge).

## One thing ...

We will migrate our build worker to use this tool. So you can be sure that this tool chain will
always stays up-to-date!

Cheers!
