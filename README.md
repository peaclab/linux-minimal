# Linux kernel

## Prereqs
``` 
sudo apt install libssl-dev gcc-arm-linux-gnueabihf bison flex
```

## To generate a bzImage run
```
make ARCH=x86_64 x86_64_defconfig
make ARCH=x868_64 -j20 bzImage
```
