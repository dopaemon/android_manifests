```bash
git clone -b lineage-23.0 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
