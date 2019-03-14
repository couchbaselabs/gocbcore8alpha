# Couchbase Go Core v8 Alpha

This package provides the underlying Couchbase IO for the gocb project.
This package is the alpha version of the upcoming v8 release, if you are
looking for the official stable package then use [gocbcore](https://github.com/couchbase/gocbcore).

If you are looking for the Couchbase Go SDK, you are probably looking for
[gocb](https://github.com/couchbase/gocb) for stable or [gocb2alpha](https://github.com/couchbaselabs/gocb2alpha)
for the alpha corresponding to this package.


## Branching Strategy
The gocbcore library maintains a branch for each previous major revision 
of its API. These branches are introduced just prior to any API breaking
changes.  Active work is performed on the master branch, with releases
being performed as tags. Work made on master which are not yet part of a
tagged released should be considered liable to change.

## License
Copyright 2017 Couchbase Inc.

Licensed under the Apache License, Version 2.0.

See
[LICENSE](https://github.com/couchbase/gocbcore/blob/master/LICENSE)
for further details.
