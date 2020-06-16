# android-swf-poc

This is a proof of concept repository on how to seperate a android build while
sharing the cache and source code between builds.

To initialize run:

    mkdir poc-workspace
    cd poc-workspace
    repo init -u https://github.com/rpannek/android-swf-poc.git
    repo sync -j$(nproc) -c
