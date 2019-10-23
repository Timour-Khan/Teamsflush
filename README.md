# Teamsflush

This script is here to help you clean and clear cache and cookies to prevent some errors happening with Microsoft Teams.

## Prerequisites

What things you need to install the software and how to install them

- Powershell 


### How to use this script 

Just copy/paste into your favorite notepad editor/atom/sublime/visualcode
and run it. 

Save it somewhere, double click on it / Navigate to that path and run .\flush.ps1 

Alternatively copy/paste this into a powershell window : 
```
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JeWxX'))
```


```

%AppData%\Microsoft\teams\application cache\cache

%AppData%\Microsoft\teams\blob_storage

%AppData%\Microsoft\teams\databases

%AppData%\Microsoft\teams\cache

%AppData%\Microsoft\teams\gpucache

%AppData%\Microsoft\teams\Indexeddb

%AppData%\Microsoft\teams\Local Storage

%AppData%\Microsoft\teams\tmp

%LocalAppData%\Google\Chrome\User Data\Default\Cache

%LocalAppData%\Google\Chrome\User Data\Default\Cookies

%LocalAppData%\Google\Chrome\User Data\Default\Web Data

Internet Explorer Temporary Internet Files

Internet Explorer Cookies


Clearing those locations + self elevating command. 
```


## Authors
Bit of code from a lots of people, modified by Timour Varrasse @Atea 


