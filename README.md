```bash
repo init --no-repo-verify --git-lfs -u https://github.com/ProjectInfinity-X/manifest -b 16 -g default,-mips,-darwin,-notdefault --depth=1
```
```bash
git clone -b infinity-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
