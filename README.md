# eyes-two-gradle
A version of the eyes-two project that can be imported and built via Gradle

This repository is pulled from the excellent tess-two project by rmtheis (https://github.com/rmtheis/tess-two).  It provides a pre-compiled .aar file which allows the eyes-two library to be incorporated into development environments where it is not possible to include the eyes-two sub-project source code.

The particular use case considered when preparing this repoistory is when building an Ionic Cordova Android native plugin, where it is easier to include the eyes-two file as a pre-complied .aar within the gradle script for the plugin.

For any projects that wish to use eyes-free from within Android Studio we recommend using the official tess-two repostiory to directly compile the eyes-two code as a sub-project.
