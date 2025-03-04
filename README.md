# PySAML2 - SAML2 for Python

[![Version](https://img.shields.io/pypi/v/pysaml2)](https://pypi.org/project/pysaml2/)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/pysaml2)](https://pypi.org/project/pysaml2/)
[![Total downloads](https://pepy.tech/badge/pysaml2)](https://pepy.tech/project/pysaml2)
[![Weekly downloads](https://pepy.tech/badge/pysaml2/week)](https://pepy.tech/project/pysaml2)
[![License](https://img.shields.io/github/license/IdentityPython/pysaml2)](https://github.com/IdentityPython/pysaml2/blob/master/LICENSE)

PySAML2 is a pure python implementation of SAML Version 2 Standard.
It contains all necessary pieces for building a SAML2 service provider
or an identity provider. The distribution contains examples of both.
Originally written to work in a WSGI environment
there are extensions that allow you to use it with other frameworks.

**Website**: https://idpy.org/

**Documentation**: https://pysaml2.readthedocs.io/

**Contribution guidelines**: [CONTRIBUTING.md][contributing]

**Security policies**: [SECURITY.md][sec]

**Source code**: https://github.com/IdentityPython/pysaml2/

**Developer guidelines**: [DEVELOPERS.md][dev]

**PyPI project**: https://pypi.org/project/pysaml2/

**License**: [LICENSE][license]


## Installation

You can install PySAML2 through pip:

```shell
pip install pysaml2
```

### External dependencies

PySAML2 works with the [`xmlsec`][xmlsec] binary.
This should be readily available in most Linux distributions:

```shell
$ apt-get install xmlsec1
$ dnf install xmlsec1-openssl
$ yum install xmlsec1-openssl
$ pacman -S xmlsec
...
```

and on MacOS through [`homebrew`][brew]

```shell
$ brew install libxmlsec1
```


## Changelog

See the [CHANGELOG][clog] to learn about the latest developments.


## Contributing

We've set up a separate document for our [contribution guidelines][contributing].


## Community

[IdentityPython][idpy] is a community around
a collection of libraries and tools to manage identity related concepts with Python code.
You can interact with the community though the [mailing list](https://lists.sunet.se/postorius/lists/idpy-discuss.lists.sunet.se/)
or on the [Slack workspace](https://identity-python.slack.com/) ([invitation](https://join.slack.com/t/identity-python/shared_invite/enQtNzEyNjU1NDI1MjUyLTM2MWI5ZGNhMTk1ZThiOTIxNWY2OTY1ODVmMWNjMzUzMTYxNTY5MzE5N2RlYjExZTIyM2MwYjBjZGE4MGVlMTM)).


## Development

We've set up a separate document for [developers][dev].


### Releasing

We've set up a separate document for our [release process][rel].


### Pre-commit

(TODO)


  [idpy]: https://idpy.org/
  [docs]: https://pysaml2.readthedocs.io/
  [contributing]: https://github.com/IdentityPython/pysaml2/blob/master/CONTRIBUTING.md
  [sec]: https://github.com/IdentityPython/pysaml2/blob/master/SECURITY.md
  [repo]: https://github.com/IdentityPython/pysaml2/
  [dev]: https://github.com/IdentityPython/pysaml2/blob/master/DEVELOPERS.md
  [pypi]: https://pypi.org/project/pysaml2/
  [license]: https://github.com/IdentityPython/pysaml2/blob/master/LICENSE
  [clog]: https://github.com/IdentityPython/pysaml2/blob/master/CHANGELOG.md
  [rel]: https://github.com/IdentityPython/pysaml2/blob/master/RELEASE.md
  [xmlsec]: http://www.aleksey.com/xmlsec/
  [brew]: https://brew.sh/
