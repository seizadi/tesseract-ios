tesseract-ios
=============

About
-----

Tesseract-ios is an IOS Library Tesseract OCR(http://code.google.com/p/tesseract-ocr/).
I wrote this since I could not find a recent Tesseract 3.02.02 distribution, so I had build it from source. There were various directions and source scattered on the web, I decided to put it all under source control and test is on the latest IOS SDK/OS.


This project is based on following:
 - [Ângelo Suzuki's blog post](http://tinsuke.wordpress.com/2011/11/01/how-to-compile-and-use-tesseract-3-01-on-ios-sdk-5/)
 - https://github.com/ldiqual/tesseract-ios

Files for Download
------------------

 - build_dependencies.sh: Cross compiling script
 - configure: Modified script for compiling Tesseract v3.02 for iOS

Requirements
------------

 - iOS SDK 8.1, iOS 7 
 - Tesseract and Leptonica libraries from the [tesseract-ios-lib](https://github.com/seizadi/tesseract-ios-lib) repo.


Installation
------------

 - Clone this repo from your project folder.
 - Download an appropriate tesseract language trained data from the following website: <https://code.google.com/p/tesseract-ocr/downloads/list> and put it in your project folder
 - You should have the following folder structure:
   Add `tesseract-ios` as a group, and `tessdata` by reference to your project.


