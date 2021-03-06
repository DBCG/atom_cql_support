# Clinical Quality Language (CQL) Support in Atom

Adds syntax highlighting to CQL files in Atom, a free and open source editor.  

![CQL Syntax Highlighting Screenshot](https://raw.githubusercontent.com/cqframework/atom_cql_support/master/screenshot.png)

## How to Install

The [cql-language](https://atom.io/packages/language-cql) package has been
published to the Atom package repository, so installation is simple:

1. If you don't have Atom, [download](https://atom.io/) and install it.
2. Install the _cql-language_ package by follow the instructions for
   [installing packages](https://atom.io/docs/latest/customizing-atom#installing-packages)
   a. The _cql-language_ package requires both a Java v1.8 runtime and a correct Java Path.
   If the installation fails to detect either, you will be prompted to download and install Java and/or set a correct Java Path.

## Using the CQL support in Atom

After you've installed the _cql-language_ package, open any _.cql_ file in Atom.
As long as the file has the _.cql_ extension, syntax highlighting will be
automatically applied.

**NOTE: Syntax highlighting makes editing and reviewing CQL files easier,
but does _not_ validate the technical or syntactic validity of the CQL
statements.  This package does not flag invalid CQL.**

## More About the Clinical Quality Language

The Clinical Quality Language (CQL) is a domain specific language for expressing
electronic clinical quality measures (eCQM) and clinical decision support rules
(CDS) in an author-friendly computable format. Find out more about CQL:
* [clinical_quality_language on GitHub](https://github.com/cqframework/clinical_quality_language)
* [Clinical Quality Expression Language at HL7](http://www.hl7.org/special/Committees/projman/searchableProjectIndex.cfm?action=view&ProjectNumber=1108)
* [S&I Clinical Quality Framework (CQF)](http://wiki.siframework.org/Clinical+Quality+Framework+Initiative)


## Local Plugin Development
* uninstall the language-cql package if you have it installed
* run `npm install` in the root directory to install dependencies
* run `apm link` to create a symbolic link from the git directories to the working directory
    * working directory can be found at <user dir>\.atom\packages\language-cql
* reload workspace to get updates (ctr-shift-f5)


## License

Copyright 2014 - 2015 The MITRE Corporation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
