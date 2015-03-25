go-virustotal
=============

VirusTotal public api interface implementation in Golang.

[![GoDoc](https://godoc.org/github.com/dutchcoders/go-virustotal?status.svg)](https://godoc.org/github.com/dutchcoders/go-virustotal)
[![Build Status](https://travis-ci.org/dutchcoders/go-virustotal.svg?branch=master)](https://travis-ci.org/dutchcoders/go-virustotal)

Usage
=====

```
go get github.com/getlantern/go-virustotal
```

You can also set the environment variable VIRUSTOTAL_APIKEY to the api key.

```
go-virustotal --apikey {key} (--debug) scan {file} {file} ...
go-virustotal --apikey {key} (--debug) rescan {hash} {hash} ...
go-virustotal --apikey {key} (--debug) report 99017f6eebbac24f351415dd410d522d
go-virustotal --apikey {key} (--debug) scan-url {url} {url} ...
go-virustotal --apikey {key} (--debug) report-url www.google.com
go-virustotal --apikey {key} (--debug) ipaddress 90.156.201.27
go-virustotal --apikey {key} (--debug) domain 027.ru
go-virustotal --apikey {key} (--debug) --resource 99017f6eebbac24f351415dd410d522d comment "How to disinfect you from this file... #disinfect #zbot"
```

## Contributions

Contributions are welcome.

## Creators 

**Remco Verhoef**
- <https://twitter.com/remco_verhoef>

- <https://twitter.com/dutchcoders>

## Copyright and license

Code and documentation copyright 2011-2014 Remco Verhoef. Code released under [the MIT license](LICENSE). 
