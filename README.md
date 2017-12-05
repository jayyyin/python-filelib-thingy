# Python FileLib Thingy
<hr>

This lib will have some file interactions

Build status of the latest master branch:
![Status](https://travis-ci.org/jayyyin/python-filelib-thingy.svg?branch=master)

This library takes a directory/file and is capable of the following
* If you enter the full path of a file (including the file) as text it'll give you the filename and extention as text
  ```python 
  getFileName(pathName)
  ```
* If you enter the full path of a file (as text) it can output the filesize in bytes (as a number)
  ```python
  getFileSize(pathName)
  ```
