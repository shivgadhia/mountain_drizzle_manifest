
## Build instructions

```
repo init -u https://android.googlesource.com/platform/manifest -b android-14.0.0.r52 --partial-clone --clone-filter=blob:limit=10M
git clone https://github.com/shivgadhia/mountain_drizzle_manifest .repo/local_manifests -b master
repo sync
```
