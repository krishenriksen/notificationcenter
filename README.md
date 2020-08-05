# Notification Center
Notification Center for TwisterOS: OSX style notification center.

![NotificationCenter Screenshot](data/screenshot.png?raw=true)

## Building, Testing, and Installation

You'll need the following dependencies:
* meson >= 0.48.2
* gobject-introspection
* libgee-0.8-dev
* libgirepository1.0-dev
* libgtk-3-dev
* valac

Run `meson build` to configure the build environment:

    meson --prefix=/usr/local -Dbuildtype=release build
    
This command creates a `build` directory. For all following commands, change to
the build directory before running them.

To build notificationcenter, use `ninja`:

    ninja

To install, use `ninja install`

    ninja install
