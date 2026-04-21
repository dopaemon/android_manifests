```bash
mkdir -p ~/LunarisAOSP && cd ~/LunarisAOSP
```
```bash
repo init -u https://github.com/Lunaris-AOSP/android -b 16.2 --git-lfs
```
```bash
git clone -b lunaris-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
