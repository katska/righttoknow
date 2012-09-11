Alavetelitheme
==============

This is the theme package for Alaveteli for the Australian deployment.

The intention is to support simple overlaying of templates and
resources without the need to touch the core Alaveteli software.

Typical usage should be limited to:

 * Putting CSS-based customisations in `public/stylesheets/custom.css`

 * Creating your own versions of non-functional pages (like "about
   us", at `lib/views/help/about.rhtml` -- and/or localised versions at
   lib/views/help/about.es.rhtml)

To install::

  ./script/plugin install git://github.com/openaustralia/alavetelitheme.git

Look in the lib/ folder of the plugin to see how the overrides happen.

Note that the `install.rb` plugin point sets up a symlink to include
local resource files within the Rails `public/` directory.

Copyright (c) 2011 mySociety and Alexander Sadleir, released under the MIT license
