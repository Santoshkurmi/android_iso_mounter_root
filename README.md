# android_iso_mounter_root
bash scrip to  mount iso in supported android phone. It is used for alternative of drivedroid if drivedroid is not supporting.

Just modify the path variables in the script to adopt with your phone. Check if the file exists in your phonne using termux or adb and update the path and 
name as it may change with different phone model

to execute the script

```
chmod +x mounter
./mounter file.iso
```
make sure to run in su mode

running may come some error like write error: no such device / resource buys.
just ignore them,its common