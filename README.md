ARIX-search-adapter
===================

[![Build Status](https://travis-ci.org/schul-cloud/arix-search-adapter.svg?branch=master)](https://travis-ci.org/schul-cloud/arix-search-adapter)
[![Dockerhub Automated Build Status](https://img.shields.io/docker/build/schulcloud/arix-search-adapter.svg)](https://hub.docker.com/r/schulcloud/arix-search-adapter/builds/)

Setup
-----

Install Go.
- [Windows][setup-windows]
- [Ubuntu][setup-ubuntu]

Testing
- https://github.com/stretchr/testify
```
go get github.com/stretchr/testify/assert
```

This code
```
go get github.com/schul-cloud/arix-search-adapter
```

Test this code
```
go test github.com/schul-cloud/arix-search-adapter/arix
```

Run the search engine server
```
go build github.com/schul-cloud/arix-search-adapter/search && search
```


[setup-windows]: http://www.wadewegner.com/2014/12/easy-go-programming-setup-for-windows/
[setup-ubuntu]: https://wiki.ubuntu.com/Go
