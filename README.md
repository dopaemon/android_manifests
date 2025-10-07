```bash
git clone -b derpfest-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
