# node-torrent

A simple bittorrent client for node.

## Features
  * Downloading based on .torrent file
  * Resume
  * Seeding
  
## In progress
  * UDP support

## TODO
  * Share ratio
  * Accurate reporting on download/upload speeds
  * Limit download/upload speeds
  * Hook up DHT, possibly using node-dht
  * Expose nice programmatic API for interacting with torrents/peers/trackers

## Usage

    var Client = require('node-torrent');
    var client = new Client();
    client.addTorrent('a.torrent');

## License 

(The MIT License)

Copyright (c) 2011 Max Stewart &lt;max.stewart@superafroman.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
