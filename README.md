BaseAIRAppLinux
===============

A minimal AIR app project, using the [airbuild Docker image](https://registry.hub.docker.com/u/jeko/airbuild/).

Requirements
------------
* Docker installed (http://docker.com/)
* Airbuild docker image installed

Setup
-----

* Edit the `setenv` file:
  * to match the version of airbuild you wan't to use.
  * remove "sudo" in the docker command if it isn't necessary.

Compile
-------

    ./compile.sh

Package for Android

    ./package_android.sh

Package for iOS

    ./package_ios.sh

While the `package_ios.sh` script is there for reference, it requires membership in the iOS developer program, certificates, etc.

