# QCouchPotato

CouchPotato server for QNAP NAS.

CouchPotato server is automatically pulled from git repository when the package is installed. The repository used is https://github.com/RuudBurger/CouchPotatoServer.

# Install

- Install Git and Python (use the community Python version from http://apps.qnap.community/)
- You can download the latest QPKG packages here https://github.com/hadim/QCouchPotato/releases.

# Contribute

- First you need to install the QDK package to your QNAP NAS. You can download it here http://wiki.qnap.com/wiki/QPKG_Development_Guidelines.

- Then clone this repository to into your NAS (use SSH access).

- Go to the folder, make your changes.

- When you're done you can build the package by executing `qbuild`.

- The package is created under `build/` directory.

- Install it by the AppCenter or via the command line `bash build/QCouchPotato_1.0.qpkg`.

# Authors

- clinton-hall
- hadim

# License

GPLv3, see [LICENSE](LICENSE).
