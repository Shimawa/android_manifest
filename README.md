
# BruhOS

 Getting Started
---------------
To get started with the BruhOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
    repo init -u git://github.com/BruhOS/android_manifest.git -b pie
```

Then sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle -jX
```
Where X is the thread your CPU can handle.

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script. By using the following command

     . build/envsetup.sh
     brunch device-codename

