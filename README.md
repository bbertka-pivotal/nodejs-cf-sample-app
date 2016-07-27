NodeJS Cloud Foundry Sample App
===============================

A sample NodeJS application to demonstrate project structure, building and deployments.

Folder Layout
-------------

* lib - Locally defined modules, business logic that isn't anything to do with Express.
* public - Anything that can be downloaded to a client/browser.
* routes - Express routes.
* test - Jasmine tests coming soon.
* views - Jade views.

Root Files
----------

* gulpfile.js - Gulp task runner task definitions.
* manifest.yml - Cloudfoundry v2 deployment descriptor.
* package.json - NPM package definition.
* server.js - The usual entry point in to the NodeJS application.
