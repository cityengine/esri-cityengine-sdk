STLDEC - CityEngine SDK Custom STL Decoder
------------------------------------------


PREREQUISITES
-------------

Before you start working with this example, please make sure you follow
the main installation instructions for the CityEngine SDK in the
README.md file at the root of this example repository. This will
explain how to get the sdk binaries and example data.


SOFTWARE REQUIREMENTS
---------------------

- see "General Software Requirements" (Linux or MacOSX)
- Make sure you use the **exact** compiler for PRT extensions


BUILD INSTRUCTIONS
------------------

1. Open a `bash` shell
1. Change into the example directory: `cd <your path to>/esri-cityengine-sdk/examples/stldec`
1. Create a build directory and change into it: `mkdir build && cd build`
1. Run cmake: `cmake ../src`
1. Compile: `make install`
1. The build result will appear in the `install` directory in parallel to the `build` directory.


INSTALLATION INSTRUCTIONS FOR CITYENGINE
----------------------------------------

1. Locate the `stldec` extension library in the `install` directory above, e.g. at:
   `<your path to>/esri-cityengine-sdk/examples/stldec/install/lib/libprt_stldec.so`
1. Copy `libprt_stldec.so` into `<CityEngine installation location>/plugins/com.esri.prt.clients.ce.gtk.linux.x86_64_1.0.0/lib/`
1. Start CityEngine and verify that STL files are now previewed in the file navigator.


LICENSING
---------

Copyright (c) 2019 Esri

You may not use the content of this repository except in compliance with the following Licenses:
  1. All content of all directories **except "examples"** is licensed under the Esri [Terms of Use](http://www.esri.com/legal/licensing-translations).
  2. All content in the "examples" directory tree is licensed under the APACHE 2.0 license. You may obtain a copy of this license at http://www.apache.org/licenses/LICENSE-2.0.
