[![Build](https://img.shields.io/travis/sapbuild/jQuery.svg?style=flat-square)](http://travis-ci.org/sapbuild/jQuery)
[![Version](https://img.shields.io/npm/v/norman-jquery.svg?style=flat-square)](https://npmjs.org/package/norman-jquery)
[![Dependency Status](https://david-dm.org/sapbuild/jQuery.svg)](https://david-dm.org/sapbuild/jQuery)
[![devDependency Status](https://david-dm.org/sapbuild/jQuery/dev-status.svg)](https://david-dm.org/sapbuild/jQuery#info=devDependencies)

jQuery-norman
==================================================

This is a custom build of [jQuery](http://jquery.com/) with only the modules included that are used in Norman.

Included modules are:
- **css**
- **dimensions**
- **offset**

This build was created according to the guidelines on the [jQuery Github page](https://github.com/jquery/jquery#how-to-build-your-own-jquery)

The build command used is:
```bash
grunt custom:-ajax,-depricated,-effects,-event,-wrap,-sizzle,-export/global
```
# BUILD on GitHub

[Click here](https://github.com/SAP/BUILD) to visit the central BUILD project on GitHub, where you can find out more!

[Click here](https://github.com/SAP/BUILD/blob/master/Contributing.md) to view the BUILD Contribution Guidelines. 
