spritesheet-samples
===================

Sampples for the Spritesheet Haxelib.


Requirements
------------
To install Spritesheet Haxelib:

    haxelib install spritesheet


Installation
------------
To install Spritesheet-Samples Haxelib:

    haxelib install spritesheet-samples

Usage
-----

### Listing Samples
To list all the Spritesheet samples use the following command:

    lime create spritesheet


### Creating Samples
If you find a sample you would like to create, you can create it using the "create" command:

    lime create spritesheet:Basics

This will create a copy of the sample within the current directory, using the same name as the sample. If you prefer, you can also specify a custom target directory:

    lime create spritesheet:Basics SpritesheetTest
    
License
------------

Spritesheet-Samples is free, open-source software under the [MIT license](LICENSE.md).

Development Builds
------------

Clone the Spritesheet-Samples repository:

    git clone https://github.com/jgranick/spritesheet-samples

Tell haxelib where your development copy of Spritesheet-Samples is installed:

    haxelib dev spritesheet-samples spritesheet-samples

To return to release builds:

    haxelib dev spritesheet-samples