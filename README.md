# EternityOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/EternityOS-Plus-Tiramisu/manifest -b 13

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

## OFFICIAL MAINTAINERSHIP ##
```
If you want to apply for official Maintainership,
Fill the form available at Official Community group
of EternityOS And Kindly wait for Team to Review 
your Form.
```
