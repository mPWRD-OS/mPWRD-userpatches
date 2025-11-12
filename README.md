# mPWRD-userpatches
Armbian + Meshtastic == mPWRD OS


## Using this repo

1. Checkout `armbian/build` and enter the dir
```sh
git clone https://github.com/armbian/build.git
cd build
```

2. Checkout this repo as "userpatches"
```sh
git clone https://github.com/mPWRD-OS/mPWRD-userpatches userpatches
```

3. Compile!
```sh
./compile.sh build luckfox-pico-mini
```
This example will build the configuration at `config-luckfox-pico-mini.conf`
