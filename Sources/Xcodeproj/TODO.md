The following features are welcome, please submit a PR:

* Our references should remain human readable, but they aren't unique enough, eg. if a module is called ProxyFoo then the TargetProxy for Foo will conflict with the Target for ProxyFoo
* “Blue Folder” everything not part of the build
* Split out tests and non-tests in Products group
* Enable code coverage
* Allow frameworks instead of dylibs and add a command line toggle
* Release configuration
* Nest Groups for module sources, eg. Sources/Bar/Foo/Baz.swift would be in Xcode groups: Source -> Bar -> Foo -> Baz.swift
* Put dependencies in Package-named sub groups of a group called "Dependencies"
