manifests
=========

Manifests for different ROMS

to init CM12 for jactivelte:

repo init -u git://github.com/CyanogenMod/android.git -b cm-12.0
mkdir .repo/local_manifests
wget https://raw.github.com/Allram/manifests/cm-12.0/local_manifest.xml -O .repo/local_manifests/local_manifest.xml
repo sync
