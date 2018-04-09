# GetterAgent
A command line tool that looks at stuff and downloads stuff. In this version, it only downloads enclosures from RSS feeds. This may be expanded in the future.

Dependencies: PHP, cURL, Linux/Unix system

```
geta command usage:

  geta download url=http://example.com/rss [options]

This command downloads all the enclosure items from an RSS feed specified by the 
url parameter. The following options are supported:

  dir=/some/directory   : saves the enclosure files to the specified location
  podcastname=SomeCast  : specify the podcast name to put in front of the file name
  log=/path/to/file.log : specify the filename of the download history file
``` 
