#Virtual disk design kata
##Requirements reminder
* A Directory has a name and stores File(s). It can add and delete files, and get all files.
* A File has a name (a string) and a size (an int).
* Directories can contain File(s) but also Directory(s). So generalize both as Resource(s).
    * We may use Composite pattern!

##Requirement 3
* We need to know the total size our virtual storage is using.
    * So add the following method to Directory: ```int totalSize();```

##Next Requirement
* [Requirement four](../blob/master/requirement-4/README.md)
