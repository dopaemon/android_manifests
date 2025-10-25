```bash
repo init -u https://github.com/AxionAOSP/android.git -b lineage-23.0 --git-lfs
```
```bash
git clone -b axion-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
