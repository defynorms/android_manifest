# DefyNorms™️

 Getting Started
---------------
To initialize your local repository, use command:

```bash
repo init -u https://github.com/DefyNorms/android_manifest.git -b ten
```

Then sync up:

```bash
repo sync --force-sync --no-clone-bundle -j$(nproc --all)
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script. By using the following command

     . build/envsetup.sh
     brunch device-codename

---------------------------------------------------------------------------------------------------------------------
