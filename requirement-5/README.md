#Virtual disk design kata
##Requirements reminder
* A Directory has a name and stores File(s). It can add and delete file(s).
* A File has a name (a string) and a size (an int).
* Directories can contain File(s) but also Directory(s). So generalize both as Resource(s).
    * Did you use Composite pattern?
* Storage should implement ```int totalSize();```.
* Storage should implement ```int totalMP3()```. A file which name finishes with “mp3” is an MP3.
    * **Did you consider Visitor pattern or domain service?** Did you implemented it in Directory?

##Requirement five
* We need to allow zip files.
* They can contain other files, zips and directories.
* The size of a zip file is defined in its creation.
* That is, zip’s filesize doesn’t depend on its content.

##Summary
* [Summary](../summary/README.md)
