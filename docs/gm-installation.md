# GraphicsMagick installation  
  
This guide will help you install the required dependencies to get started!  
  

## Linux (Debian based)  
  
For linux users, you can run the following commands on your terminal.  
  
```
$ sudo apt-get update
$ sudo apt-get install ghostscript
$ sudo apt-get install graphicsmagick
```
  
Once everything is installed, the library should work as expected.  
  
## Mac OS  
  
For rich people, you can run the following commands on your terminal.  
  
```
$ brew update
$ brew install gs graphicsmagick
```  
  
Once everything is installed, the library should work as expected.  
  
## Windows  

For windows users.. open the links and download installers.

- Download Ghostscript **9.52** for Windows: https://github.com/ArtifexSoftware/ghostpdl-downloads/releases/tag/gs952
- Download GraphicsMagick for Windows: http://ftp.icm.edu.pl/pub/unix/graphics/GraphicsMagick/windows/

Add Windows Environment Variables for your version(****)
- C:\Program Files\gs\gs****\bin
- C:\program files\graphicsmagick-****

An error occurred when the Ghostscript version was 9.53 or later.

## AWS Lambda  
  
For lambda you can add the required libraries using [layers](https://docs.aws.amazon.com/lambda/latest/dg/invocation-layers.html). There are prebuilt, community driven layers for both [GraphicsMagic](https://github.com/rpidanny/gm-lambda-layer) and [Ghostscript](https://github.com/shelfio/ghostscript-lambda-layer).
