## mozilla firefox

Mozilla Firefox is a free and open-source web browser developed for Windows, OS X, and Linux. This repository contain freeze firfox versions for [minos](http://minos.io), refer to [mozilla](http://mozilla.org/firefox) for the latest one.

## Quick start

### On Ubuntu (only LTS versions)

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```

2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install firefox28
   ```

3. Enjoy ☺!

### On other Linux distributions

1. Uncompress `tar jxf firefox${version}/firefox${arch}.tar.bz2`

2. Launch `./firefox${arch}/firefox`

### Why

Since [Australis](https://blog.mozilla.org/ux/2013/11/australis-is-landing-in-firefox-nightly/) landing on Firefox, Mozilla has been taking decisions to improve its acceptance on new user bases, some of those decisions however affect power users who are used to control every detail in its browsing experience and don't accept easily intrusive plugins.

Unfortunately when looking around, other options look even worst, so this freeze version is hosted and used by default on Minos till FF makes sense again or there exist a compeling alternative. See https://github.com/minos-org/firefox-minos-settings to get an idea of what may be an appealing alternative.
