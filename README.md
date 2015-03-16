Installation
============

0. Download and install [node.js and npm](http://nodejs.org/). Version 0.10.x will do.
4. Open command line window in this folder or `cd` to it.
5. Install grunt-cli: `npm install -g grunt-cli`. Check if everything is ok with `grunt --help`. Use `sudo` on *nix-like systems.
6. Install project dependencies: `npm install`.
7. Run `grunt` for manual build.
8. Run Grunt serve to start server
=======


What's inside?
==============

* Reasonable structure for backendless projects.
* Latest [jquery](http://jquery.com), [underscore](http://underscorejs.org) and [requirejs](http://requirejs.org).
* Automatic LESS compiler with source maps generation.
* Automatic r.js optimizer.
* Useful and pre-configured grunt tasks.
* Reasonable defaults for git.
* HTML5 `index.html`, clean but ready to go.
* Separate, unminified files in development, and
* Compiled and minified files served to end-user.


Setup
============

0. Clone this repo (or download and unzip).
1. Download and install [node.js and npm](http://nodejs.org/). Version 0.10.x will do.
2. Install grunt-cli: `npm install -g grunt-cli`. Check if everything is ok with `grunt --help`. You may want to use `sudo` on *nix-like systems.
3. Open command line window in this folder or `cd` to it.
4. Install project dependencies: `npm install`. This can take some time.
5. Run build tool with `grunt watch`, and fire up your favorite editor/IDE. Grunt will watch for changed files and will rebuild styles and scripts accordingly.
6. Run `grunt` for manual build.
7. Do not forget to change version and name in `package.json`.
8. Do not forget to change git remote.

FAQ
===
* *Why not H5BP?*<br/>
  H5BP is great, but includes A LOT of stuff which rarely needed. I mean, "Adobe Cross Domain", wth.<br/>

* *Why not [Yeoman](http://yeoman.io/)?*<br/>
  Sometimes Yeoman seems like an overkill.<br/>

* *Why LESS, not SASS/Compass?*<br/>
  Not unless they port it to node.js.<br/>

* *Ok, but include Stylus then.*<br/>
  Planned.<br/>

* *What about CoffeeScript?*<br/>
  You're welcome to make this contribution:)<br/>

* *Modernizr, html5-shim, es5-shim?*<br/>
  Not every project need those, but planned.<br/>

* *Live editing?*<br/>
  Planned.<br/>

Troubleshooting
===============
* *I'm behind evil corporate proxy, npm doesn't work!*<br/>
  Configure npm to use proxy with your domain credentials: `npm config set proxy http://<username>:<password>@<proxy_addr_or_ip>:<proxy_port>/`. You may also need to tell npm to use http when connecting to registry: `npm config set registry http://registry.npmjs.org/`<br/>

* *I have added new file.less but it doesn't work*<br/>
  This is problem with grunt-contrib-watch and soon will be fixed. At the moment, quit `grunt watch` and start it again.
