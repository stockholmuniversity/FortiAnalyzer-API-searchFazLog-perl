# FortiAnalyzer-API-searchFazLog-perl
Simple Perl script to search the Faz log and receive the result in JSON

# Requirements
* Following external libraries `JSON`, `Config::JSON` and `SOAP::Lite`. For Debian that is `apt install libsoap-lite-perl libconfig-json-perl`.
* An account in the FortiAnalyzer with permissions to access the API and read logs.

# Configuration
* Edit [FortiAnalyzer-API-searchFazLog-config.json](FortiAnalyzer-API-searchFazLog-config.json)

# Usage
* Run [FortiAnalyzer-API-searchFazLog-config](FortiAnalyzer-API-searchFazLog)
```
$ FortiAnalyzer-API-searchFazLog --startDate="1970-01-01 00:00" --endDate="2017-11-06 13:10" --searchCriteria="dstip=127.0.0.1"
```

# Author
Johan Wassberg <jocar@su.se>
