## JSON-Spirit Packaging ##

This project provides a script which will package JSON-Spirit headers in a similar manner to the other `build-*` projects.  It contains as a submodule, [json-spirit][json-spirit-release] git project.

[json-spirit-release]: https://github.com/toonetown/json-spirit

### Requirements ###

This library is header-only and the script just copies the headers into a package.

     
### Build Steps ###

You can package this by using the `build.sh` script:

    ./build.sh [/path/to/json-spirit-dist] package </path/to/output/directory>

Run `./build.sh` itself to see details on its options.

You can modify the execution of the scripts by setting various environment variables.  See the script sources for lists of these variables.
