mathphreak/ServerlessWebappTemplate
===================================

A somewhat opinionated template for serverless web apps.

Uses CoffeeScript, Jade, and LESS as sources, then compiles using Grunt into JS, HTML, and CSS, respectively.

Comes with jQuery and Bootstrap, with Font Awesome instead of Glyphicons.
Also has Underscore and Backbone.

Usage
-----

    npm install
    grunt

This will automatically compile everything, launch a Web browser pointed to the development server, and recompile and reload as needed.

Then, simply edit any of the files from `src/`.

Deployment
----------

Run `grunt dist`, then distribute `out/` however you like.  `out/index.html` should work if you just open it directly in a Web browser; all the paths are relative.
