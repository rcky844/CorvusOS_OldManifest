To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/du-rex/android_manifest.git -b 10

To sync the repository, use this command:
-----------------------------------------

    repo sync --force-sync --no-tags --no-clone-bundle

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch du_device-userdebug
    make corvus
