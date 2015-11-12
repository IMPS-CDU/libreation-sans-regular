sherpa
======

Third-party libraries and dependencies for PhET Simulations

By PhET Interactive Simulations
http://phet.colorado.edu/

[List of the third-party code, fonts, images and audio](third-party-licenses.md)

For developers: when adding a new library or changing third-party-licenses.json, please run the `grunt report-third-party` command with the
`--copy-from-build` option after running a `chipper/bin/grunt-all.sh --lint=false`.  Note that this grunt task has a required
 argument which is the directory to copy the HTML files to.

### Documentation
The [PhET Development Overview](http://bit.ly/phet-development-overview) is the most complete guide to PhET Simulation Development. This guide includes how
to obtain simulation code and its dependencies, notes about architecture & design, how to test and build the sims, as well as other important information.

### License
See the [license](LICENSE)
