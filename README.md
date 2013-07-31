# Bench

> WARNING: This is very much alpha!

A combination of [HTTPerf.js](http://mervine.net/projects/npms/httperfjs),
[YSlow.js](http://mervine.net/projects/npms/yslowjs) and
[Phantomas](https://github.com/macbre/phantomas) (a
[PhantomJS](http://phantomjs.org/) backed client performance metrics
scrapper). Using [NodeUnit](https://github.com/caolan/nodeunit) to test a
page against configurated thresholds and fail if not met. Additionally,
basic graphing of last 10 results.

### Install

1. Install Node.js
2. Clone Repo:

    git clone https://github.com/jmervine/bench.git
    cd bench
    make setup

### Usage

1. Update configuration (`./config.json') to reflect your host, path and
thresholds.
2. Run:

    make bench

3. Open `./index.html` in a browser to view graph of multip runs.

