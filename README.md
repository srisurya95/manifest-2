MerkMod
===========

To initialize your local repository using the MerkMod trees, use a command like this:
````bash
repo init -u git://github.com/merkmodmanifest.git -b merk-3.0
```
Then to sync up:
````bash
repo sync
```
Finally to build:
````bash
./build.sh device_codename
