# Our Swift Style Guide

### Crashing code:
[Swift fatalError is a fatal error](https://lapcatsoftware.com/articles/fatalError.html)
Prefered to use `preconditionFailure()` or `assertionFailure()` depending on whether you want your app to terminate in release builds.
