gluon nightly reboot script
===========================

This script wil create a micron.d entry 'nightboot' which reboots the node each day at 4 a.m.

<br>
GLUON_SITE_FEEDS="fflip"<br>
PACKAGES_FFLIP_REPO=https://github.com/FreifunkLippe/packages.git<br>
PACKAGES_FFLIP_COMMIT=*/missing/*<br>
PACKAGES_FFLIP_BRANCH=master<br>

With this done you can add the package *gluon-nightboot* to your site.mk

