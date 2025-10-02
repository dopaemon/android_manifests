```bash
git clone -b cherish-16 https://github.com/dopaemon/android_manifests.git .repo/local_manifests
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags --fetch-submodules -j$(nproc --all)
```
