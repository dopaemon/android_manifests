```bash
repo init --depth=1 --no-repo-verify -u https://github.com/CherishOS/android_manifest.git -b sixteen -g default,-device,-mips,-darwin,-notdefault --git-lfs
```
```bash
git clone -b cherish-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
