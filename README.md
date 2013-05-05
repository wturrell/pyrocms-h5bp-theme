For when *Minimal* is too fancy...

An (unofficial) barebones copy of HTML5 Boilerplate as a PyroCMS theme.  
This is the stripped (comment free) version.  Header, footer and metadata partials only.

Uses: H5BP v4.2.0 (8 Apr 2013)
Tested with: PyroCMS Community Edition 2.2.1-dev (3 May 2013, commit a9e347)

It includes all that's in H5BP except:
- crossdomain.xml
- favicon.ico and apple-touch icons
- robots.txt and humans.txt

(All of which need to go in your site root anyway, rather than the /themes dir)

I've added jQuery Migrate (runs in 'development' environment only) to help you find 
and fix any jQuery 1.9 compatibility problems given it's quite new.

For more on HTML5 Boilerplate, see http://www.h5bp.com/
Major PyroCMS releases are announced in the PyroCMS blog: https://www.pyrocms.com/blog

Installation
============

1. Copy all files to /addons/shared_addons/themes/ (create a new subdirectory for them)
2. Go to http://www.*yoursite*.com/admin/addons/themes
