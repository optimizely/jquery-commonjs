# jquery-commonjs
Older versions of jquery packaged as commonjs modules.

These legacy jquery modules have been modified to default export the jquery object($).  These modules also will not add `jQuery` or `$` to the global namespace (window).  For all versions the source code has been minified.  Note that starting with jquery version 1.10 the default behavior changed to not set the jQuery globals in a commonjs module environment, so starting with that version the stock jquery code can be used without concern over the setting of the jQuery global variables.

The following jquery versions are available (via the following git tags and associated package.json git URLs)
- `v1.7.2`: `git://github.com/optimizely/jquery-commonjs.git#v1.7.2`
- `v1.8.3`: `git://github.com/optimizely/jquery-commonjs.git#v1.8.3.1`
- `v1.9.1`: `git://github.com/optimizely/jquery-commonjs.git#v1.9.1`
