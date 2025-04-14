# Photo Drive

Many digital picture frames support Google Photos, but often have
either a required subsription or a limit on the number of photos.  It
is also common for them to support USB drives with photos.  The
purpose of this project is to leverage the USB support and the Google
Photos API to synchronize arbitrarily sized albums.

The project provides a web server to run as a service that
periodically synchronizes photos from Google Photos with local
storage.  It then exposes these photos as a mass storage device using
the Linux USB Gadget library.  This allows you to plug in a Raspberry
Pi to a picture frame and sync whatever Google Photos you want.

TODO: Fill out remaining docs.
