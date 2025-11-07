```bash
repo init -u https://github.com/Project-Mist-OS/manifest -b bp2a --git-lfs
```
```bash
git clone -b mist-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
