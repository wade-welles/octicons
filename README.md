octicons
========

[![Build Status](https://travis-ci.org/shurcooL-legacy/octicons.svg?branch=master)](https://travis-ci.org/shurcooL-legacy/octicons) [![GoDoc](https://godoc.org/github.com/shurcooL-legacy/octicons?status.svg)](https://godoc.org/github.com/shurcooL-legacy/octicons)

Package octicons provides GitHub Octicons.

It's a Go package that statically embeds GitHub Octicons data, exposing it via an http.FileSystem.

Deprecated: GitHub has deprecated the icon font version of Octicons in favor of SVG.
See https://github.com/primer/octicons/issues/108 and https://github.com/blog/2112-delivering-octicons-with-svg.
Use [`github.com/shurcooL/octicon`](https://godoc.org/github.com/shurcooL/octicon) instead, which provides Octicons in SVG format.

Installation
------------

```bash
go get -u github.com/shurcooL-legacy/octicons
```

License
-------

-	[MIT License](https://opensource.org/licenses/mit-license.php)
