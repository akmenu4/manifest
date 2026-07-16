# akmenu4

To set up the development environment:

1. Install the BlocksDS toolchain: https://blocksds.skylyrac.net/docs/setup/
1. Download repo and add it to PATH: https://storage.googleapis.com/git-repo-downloads/repo
1. Create a directory for akmenu4
1. Enter the directory, then run the following:
    ```
    repo init -u https://github.com/akmenu4/manifest
    repo sync -j`nproc`
    ```
1. Run `make` to build for a device
