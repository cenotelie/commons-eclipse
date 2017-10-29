# Cénotélie Commons - Eclipse Update Site #

[Cénotélie Commons](https://bitbucket.org/cenotelie/commons) is a set of useful Java API that can be leveraged for other projects.
This repository defines the Eclipse Update Site that can used within Eclipse to give access to the following bundles as Eclipse plugins:

* Bundle [fr.cenotelie.hime:redist](https://bitbucket.org/cenotelie/hime) as Eclipse plugin fr.cenotelie.hime.redist
* Bundle [fr.cenotelie.hime:hime-language-server](https://bitbucket.org/cenotelie/hime-language-server) as Eclipse plugin fr.cenotelie.hime.language-server
* Bundle [fr.cenotelie.commons:commons-utils](https://bitbucket.org/cenotelie/commons) as Eclipse plugin fr.cenotelie.commons.utils
* Bundle [fr.cenotelie.commons:commons-jsonrpc](https://bitbucket.org/cenotelie/commons) as Eclipse plugin fr.cenotelie.commons.jsonrpc
* Bundle [fr.cenotelie.commons:commons-lsp](https://bitbucket.org/cenotelie/commons) as Eclipse plugin fr.cenotelie.commons.lsp


## How do I use this software? ##

The updates sites are deployed to:

```
https://nexus.cenotelie.fr/repository/raw/p2/cenotelie-commons/${version}
```

Deployed versions are:

* [Version 2.0.1](https://nexus.cenotelie.fr/repository/raw/p2/cenotelie-commons/2.0.1)


## Repository structure ##

* `fr.cenotelie.commons.feature`: Eclipse Feature for the bundles.
* `fr.cenotelie.commons.updatesite`: Eclipse Update Site definition


## How to build ##

To build the artifacts in this repository using Maven:

```
$ mvn clean install -Dgpg.skip=true
```


## License ##

This software is licenced under the Lesser General Public License (LGPL) v3.
Refers to the `LICENSE.txt` file at the root of the repository for the full text, or to [the online version](http://www.gnu.org/licenses/lgpl-3.0.html).
