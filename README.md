# motion-photo-extractor

## What this does

It's a command line ruby script that splits your Samsung motion photos in to a (now smaller) jpg and a mp4. Samsung saves files into 

The files will be saved in the same folder the original image.

## Setup

    - You want Ruby on you path (tested with 2.4.3)
    - Install Bundler if you don't have it ```$ gem install bundler```
    - Then run a ```$ bundle install```

## Examples of use

$ motionPhotoExtractor.rb -p /Users/YourName/Desktop/Desktop/FolderWithMotionPhotosInIt

or

$ motionPhotoExtractor.rb -p /Users/YourName/Desktop/Desktop/FolderWithMotionPhotosInIt/OnePhoto.jpg

## Options

```
Usage: motionPhotoExtractor.rb [options]
-р, --рath-PАТН    Path of the image / folder of images you want to extract the motion from
-d, --delete       Keep only pictures (remove mp4 and original image)
-h, --help         Prints this help
```
