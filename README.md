# GoogleDrive Extension
An extension to download, upload, edit, modify and delete files from your google drive.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/Drive%20logo.png"/>

## Extension Properties

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/aix.png"/>

You need to set folder id from Block Section or from Designer Section.

<table>
  <tr>
    <td><img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/property-1.png"/></td>
    <td><img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/property-2.png"/></td>
  </tr>
</table>

<details>
  <summary><b>Total Functions & Events</b></summary>

Total 13 functions and 11 events available now.

<table>
  <tr>
    <td><img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/all-methods.png"/></td>
    <td><img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/all-events.png"/></td>
  </tr>
</table>
</details>

## Requirements
Share your folder access with anyone on internet. If you want to upload or write files from extension then you need to give editor access. Otherwise you can give viewer access.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/Requirements.png"/>

## Get Files
Using this block you can get all files from your folder.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/get-files.png"/>

<li> <b>name</b> - It's return the name of files.
<li> <b>size</b> - It's return the size of files in byte formats.
<li> <b>link</b> - It's return the direct download link of files.
<li> <b>date</b> - It's return the created date of files.

## Rename File
You can rename your file using file Id.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/rename-file.png"/>

<li> <b>id</b> - It's return the id of given file.
<li> <b>name</b> - It's return the new name of given file.

## Delete File
You can delete your uploaded file using file Id.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/delete-file.png"/>

<li> <b>id</b> - It's return the id of deleted files
<li> <b>isDeleted</b> - It's return bolean result of deletion action.

## Upload File
You can upload any type of file using this block and also you can set custom name of file.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/upload-file.png"/>

<li> <b>id</b> - It's return the id of uploaded file.
<li> <b>name</b> - It's return the new name of uploaded file.
<li> <b>link</b> - It's return the direct download link of uploaded file.
<li> <b>size</b> - It's return the size of uploaded file.

## GetDirectDownloadLink
Using this you can get direct download link of any file using file Id.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/get-direct-download-link.png"/>

## Create Folder
Using this block you can create new folder in any root folder using root folder id.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/create-folder.png"/>

<li> <b>NewFolderId</b> - It's return the id of created folder.
<li> <b>NewFolderName</b> - It's return the created folder name.
<li> <b>rootFolderId</b> - It's return the root folder id to handle user's activity.

## Delete Folder
Using this block you can delete any folder using it's id.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/delete-folder.png"/>

<li> <b>folderId</b> - It's return the id of deleted folder.
<li> <b>isDeleted</b> - It's return boolean.

## Get Folders
Using this block you can get folders from your drive root folder.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/get-folders.png"/>

<li> <b>rootFolderId</b> - It's return the id of root folder.
<li> <b>ids</b> - It's return the list of folders ids.
<li> <b>names</b> - It's return the list of folders names.
<li> <b>sizes</b> - It's return the list of folders sizes.

## Move File
Using this block you can move file from one folder to another folder.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/move-file.png"/>

<li> <b>folderId</b> - It's return the id of folder.
<li> <b>fileId</b> - It's return the id of file.

## Move Folder
Using this block you can move your folder to another folder.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/move-folder.png"/>

<li> <b>rootFolderId</b> - It's return the id of root folder.
<li> <b>childFolderId</b> - It's return the id of child folder.

## Rename Folder
Using this block you can rename your folder name.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/rename-folder.png"/>

<li> <b>folderId</b> - It's return the id of folder.
<li> <b>name</b> - It's return the new name of folder.

## Encode & Decode
Using this block you can protect your folder ids. Set level (1-100) and password length must be 5 or more.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/encode-decode.png"/>

## Failed
It rises if got any error.

<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/failed.png"/>

<li> <b>functionName</b> - It's return the function name which function got the error.
<li> <b>error</b> - It's return the error string.

## More extension

<a href="https://github.com/jewelshkjony?tab=repositories">See more extensions</a>

## Extension specifications:
<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/download.png"/> <a href="https://t.me/jewelshkjony">com.jewel.googledrive</a>(79.8 KB) \
<b>Version:</b> 5.1.2\
<b>Price:</b> $10 USD (Standard Edition) - <sub>You'll not get next updates are free. You've to pay again. Also It has validity limitation.</sub>\
<b>Price:</b> $20 USD (Premium Edition) - <sub>Available to get futures updates for free. No limitation remain.</sub>\
<b>Last amendment:</b> 23 August 2022\
<b>Supported builder:</b> <a href="https://www.kodular.io/">Kodular</a>, <a href="https://niotron.com/">Niotron</a>, <a href="https://appzard.com/">AppZard</a>, <a href="https://androidbuilder.in/">AndroidBuilder</a>, <a href="http://ai2.appinventor.mit.edu/">App Inventor</a> and it's other distributions.

## 📫 How to reach me -

<a href="https://t.me/jewelshkjony">Telegram</a> | <a href="https://wa.me/8801775668913">WhatsApp</a> | <a href="https://fb.com/jewelshkjony">Facebook</a> | <a href="https://m.me/jewelshkjony">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony">Youtube</a>

## Global Payment Method
<a href="https://www.xoom.com/bangladesh/send-money">Xoom</a> | <a href="https://wise.com/">TansferWise (Wise)</a> | <a href="http://share.payoneer.com/nav/kJkLyppKLt-FTUg-P9xnUd76yT4iWQiym2irI42PLM7uQWXuVsWvSOABMvVykU5hbFiDGSULXNdI3-yRM7JVhA2">Payoneer</a>

### Bangladeshi Payment Method
Bangladeshi user can send money using <a href="https://bka.sh/next?c=signup&uuid=C1CC9JVT1">bkash</a> | <a href="https://play.google.com/store/apps/details?id=com.konasl.nagad">Nagad</a> | <a href="https://play.google.com/store/apps/details?id=com.dbbl.mbs.apps.main">Rocket</a>.
Use this phone number to send money.

````java
+8801775668913
````

Remember accounts are personal, so you've to use send money option.
