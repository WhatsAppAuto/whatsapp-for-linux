# whatsapp-for-linux

An unofficial WhatsApp linux client written in C++ with the help of gtkmm-3.0 and webkit2.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/whatsapp-for-linux)

[![Action Status](https://github.com/eneshecan/whatsapp-for-linux/workflows/Build/badge.svg)](https://github.com/eneshecan/whatsapp-for-linux/actions)
[![Action Status](https://github.com/eneshecan/whatsapp-for-linux/workflows/Install/badge.svg)](https://github.com/eneshecan/whatsapp-for-linux/actions)

![App Window](https://github.com/eneshecan/whatsapp-for-linux/blob/master/screenshot/app.png)


## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md).


## Dependencies

* cmake >= 3.8
* gtkmm-3.0
* webkit2gtk-4.0


## Build & Run

### Development

1. Create a debug build directory and go into it. `mkdir -p build/debug && cd build/debug`
2. Build cmake. `cmake -DCMAKE_BUILD_TYPE=Debug ../..`
3. Build makefile. `make`
4. Run. `./whatsapp-for-linux`

### Local installation
If you want to install it locally, use `make install` inside the build directory after
building (You'll probably need administrator privileges for this).


## Using whatsapp-for-linux
Check out [releases](https://github.com/eneshecan/whatsapp-for-linux/releases) for available packages.
