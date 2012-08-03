Introduction
============

This is a patch of nginx's dso module(for nginx 1.2.2).


Installation
============
 Grab the nginx source code from nginx.org (<http://nginx.org/>), for
 example, the version 1.2.2 (see nginx compatibility), and then build the
     source with this feature:

        $ wget 'http://nginx.org/download/nginx-1.2.2.tar.gz'
        $ tar -xzvf nginx-1.2.2.tar.gz
        $ cd nginx-1.2.2/
        $ patch -p1 < /path/to/nginx_dso_1.2.2.patch

        $ ./configure

        $ make
        $ make install

Document
============
please read this: https://github.com/monadbobo/tengine/blob/dso/docs/modules/ngx_dso_module.md
