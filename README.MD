Get The iSH App From https://apps.apple.com/us/app/ish-shell/id1436902243
```
apk add wget openssl git zip unzip build-base zlib-dev openssl-dev cmake
wget https://appinstallerios.com/Zsign/zsign.zip
unzip zsign.zip
cd zsign
mkdir build; cd build &&
cmake .. &&
make
cp zsign /bin
echo Finished!
```

The compiling part might take 5 minutes so don't let your device turn off

Once the comping process is complete you can run ./zsign
