### How to build:
First of all [clone Minimal TWRP manifest repo](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git)

Then clone this local manifest

```cd $working_dir && git clone https://github.com/AOUP-AndroidOpenUmiProject/local_manifests.git -b TWRP .repo/local_manifests && repo sync --force-sync```

### Once synced:

* cd $working_dir
* lunch omni_yourdevice(n383bt)
* mka recoveryimage
