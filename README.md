```bash
repo init -u https://github.com/Lunaris-AOSP/android -b 16 --git-lfs --depth=1
```
```bash
git clone -b lunaris-16-floral https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags --fetch-submodules -j$(nproc --all)
```
