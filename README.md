karma-failed-reporter
=====================

List all failed specs with the errors. For me, this is extremely useful because
I have hundreds of tests, and this makes finding the failed tests a lot easier.

Include this specrunner in your `karma.conf.js` like so:

    reporters: ['failed'],
