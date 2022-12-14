# Navicat Keygen - How to build?

## 1. Prerequisites

1. Please make sure you have installed following libraries:

   * `capstone`
   * `keystone`
   * `rapidjson`
   * `fuse2`

   If you use Arch Linux, you can install them by:

   ```console
   # install capstone keystone rapidjson
   $ sudo pacman -S capstone keystone rapidjson fuse2
   ```

2. Your gcc supports C++17 feature.

## 2. Build

```console
$ git clone https://github.com/eurislee/navicat-keygen-tools.git
$ cd navicat-keygen-tools
$ make all
```

You will see executable files in `bin/` directory. 
