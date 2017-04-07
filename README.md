If you are facing errors while delivering iOS applications using cocoapods to iTunes Connect in the way:

"Invalid Bundle Executable. The executable file '<name>.app/Frameworks/<PodFramework>.framework/<Something>' contains incomplete bitcode. To compile binaries with complete bitcode, open Xcode and choose Archive in the Product menu."

there are 2 options according to http://stackoverflow.com/questions/32640149/disable-bitcode-for-project-and-cocoapods-dependencies-with-xcode7. One is to embed bitcode into build cocoapods which will be done with installing this dependency automatically.

npm install --save nativescript-pods-embedbitcode