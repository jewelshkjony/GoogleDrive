# Google Drive Extension
An extension to download, upload, edit, modify and delete files from your google drive.\
Support all Android version. (Tested with Android 10, 11, 12, 13)
* **

![image](https://user-images.githubusercontent.com/75406851/222394514-601f9f67-7429-4a7d-8e88-1a14fec421da.png)

## 🧾 Extension Properties
You need to set folder id from Block Section or from Designer Section.

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/75406851/222394602-d8528ad0-efc3-4611-b627-1ed8824e5cbc.png"></td>
    <td><img src="https://user-images.githubusercontent.com/75406851/222394661-5c912009-707f-4875-b146-97eb1186680e.png"></td>
  </tr>
</table>

<br>

<details>
  <summary><b> ⚠️ Requirements</b></summary>
Share your folder access with anyone on internet. If you want to upload or write files from extension then you need to give editor access. Otherwise you can give viewer access.

![image](https://user-images.githubusercontent.com/75406851/222394780-e8703a09-1d49-468b-9ee8-644831211c56.png)

</details>

## 📂 Upload File
Using this block you can upload any file from storage.

![image](https://user-images.githubusercontent.com/75406851/222394849-f23daaf7-df24-46e6-8049-883294d30e49.png)

`fileType` - Set specific file type to pick file from storage.

![image](https://user-images.githubusercontent.com/75406851/222394892-ac228eea-fbd9-48d9-a101-ac5958b9cbae.png)

![image](https://user-images.githubusercontent.com/75406851/222394952-0bf75e35-963e-4eec-a077-81755f5275c8.png)

`fileId` - It's return the id of uploaded file.\
`file Name` - It's return the name of uploaded file.\
`fileUrl` - It's return the url of uploaded file.\
`file Size` - It's return the size of uploaded file.

## 📂 Upload Multiple Files
Using this block you can upload multiple files in single request.

![image](https://user-images.githubusercontent.com/75406851/222395016-ee000614-d915-4905-8ff0-5f81714cd08e.png)

`fileType` - Set specific file type to pick file from storage.

![image](https://user-images.githubusercontent.com/75406851/222395035-24f2a367-b0d7-4c5c-8a56-3c505480c873.png)

![image](https://user-images.githubusercontent.com/75406851/222395064-d0e8a53f-8829-4ef0-aa2f-187945226b77.png)

`fileIds` - It's return the ids of uploaded files as list.\
`fileNames` - It's return the names of uploaded files as list.\
`file Sizes` - It's return the sizes of uploaded files as list.\
`fileUrls` - It's return the urls of uploaded files as list.

## ✖️ File Picker Canceled
It's triggered when user click on back press to cancel picking file.

![image](https://user-images.githubusercontent.com/75406851/222395140-beb1bd61-5a67-45a6-ac65-b2ce905f8995.png)

`function Name` - It's return the name of function.

## 📸 Capture Photo To Upload
Using this blocks you can take photo using phone camera to upload it into Drive folder. Also you can compress photo before uploading.

![image](https://user-images.githubusercontent.com/75406851/224277961-5dffdbd6-93bb-49e0-83eb-6164acf9b4d3.png)

`quality` - Enter quality amount as integer from 0 to 100.

![image](https://user-images.githubusercontent.com/75406851/224278029-38fc1325-6418-426d-97dc-ffbba72142f9.png)

`fileId` - It’s return the id of uploaded file.\
`file Name` - It’s return the name of uploaded file.\
`fileUrl` - It’s return the url of uploaded file.\
`file Size` - It’s return the size of uploaded file.

## ✖️ Photo Capture Canceled
It’s rises when user cancel photo capturing or click on back press.

![image](https://user-images.githubusercontent.com/75406851/224278368-a5999747-d171-4913-80bb-bab4369253bd.png)

`function Name` - It’s return the name of function.

## 🔗 Upload File By Url
Using this block you can upload file from internet by using file url.

![image](https://user-images.githubusercontent.com/75406851/222395175-af8970eb-4021-47f1-ae1c-687f7de23223.png)

`fileUrl` - Enter file url to upload it into drive folder.

![image](https://user-images.githubusercontent.com/75406851/222395200-668c648a-da6f-46ba-8333-ee7a04545cff.png)

`fileId` - It's return the id of uploaded file.\
`file Name` - It's return the name of uploaded file.\
`fileUrl` - It's return the url of uploaded file.\
`file Size` - It's return the size of uploaded file.

## 🔗 Upload Multiple Files By Url
Using this block you can upload multiple files from internet in single request.

![image](https://user-images.githubusercontent.com/75406851/222395261-43be8b13-9691-4257-a51d-348beb5d4c8b.png)

`fileUrls` - Enter file urls as list.

![image](https://user-images.githubusercontent.com/75406851/222395278-d26866d7-6dd8-4d21-bba7-5e31817e039a.png)

`fileIds` - It's return the ids of uploaded files as list.\
`fileNames` - It's return the names of uploaded files as list.\
`file Sizes` - It's return the sizes of uploaded files as list.\
`fileUrls` - It's return the urls of uploaded files as list.

## 🔁 Update File
Using this block you can modify a file which already uploaded into your drive.

![image](https://user-images.githubusercontent.com/75406851/222395356-04c76cfd-746b-4518-b8a7-421e3b6f8429.png)

`fileId` - Enter that file id which file you want to update.\
`fileType` - Set specific file type to pick file from storage.

![image](https://user-images.githubusercontent.com/75406851/222395385-ad926014-5dec-4eaa-9df5-7aabeaccdb3d.png)

![image](https://user-images.githubusercontent.com/75406851/222395418-82c2c185-36ef-47c8-9052-5fd6f4208e6d.png)

`fileId` - It's return the updated file id.

## ⬇️ Get Files
Using this block you can get all files from your folder.

![image](https://user-images.githubusercontent.com/75406851/222395489-7999b923-d791-45d2-af1f-77768c04e09f.png)

![image](https://user-images.githubusercontent.com/75406851/222395514-3db856e8-4933-4759-ab6b-1573775a5139.png)

`fileNames` - It's return the names of files as list.\
`fileSizes` - It's return the sizes of files in byte formats as list.\
`fileUrls` - It's return the download links of files as list.\
`lastUpdateDates` - It's return the last update dates of files as list.\
`fileIds` - It's return the ids of files as list.

## ✂️ Delete File
You can delete your uploaded file using file Id.

![image](https://user-images.githubusercontent.com/75406851/222395582-b1d01ba1-b057-4443-95b1-8ca3fc2027dd.png)

`fileId` - Enter file id.

![image](https://user-images.githubusercontent.com/75406851/222395617-44b86dee-912f-4be4-b5ff-af4265eeae29.png)

`fileId` - It's return the id of deleted file.\
`isDeleted` - It's return bolean result of deletion action.

## ✍️ Rename File
You can rename your file using file Id.

![image](https://user-images.githubusercontent.com/75406851/222395725-263a8bb3-b50a-4c25-bb0a-cd3bc49be592.png)

`fileId` - Enter file id.\
`new Name` - Enter new name.

![image](https://user-images.githubusercontent.com/75406851/222395764-26469ef0-e2fc-432b-8afc-3f4eeb11f897.png)

`fileId` - It's return the file id.\
`file Name` - It's return the file name.

## 🔗 GetDirectDownloadLink
Using this you can get direct download link of any file using file Id.

![image](https://user-images.githubusercontent.com/75406851/222395815-98c09888-e572-4dd1-804d-2018d33bb08f.png)

`fileId` - Enter file id.

## 📁 Create Folder
Using this block you can create new folder in any root folder using root folder id.

![image](https://user-images.githubusercontent.com/75406851/222395869-ecfc2771-a3f9-49a1-aeb0-6554314cab2c.png)

`rootFolderId` - Enter root folder id.\
`newFolderName` - Enter new folder name.

![image](https://user-images.githubusercontent.com/75406851/222395886-ae8eeedc-62d3-4643-93c0-4fb818907144.png)

`newFolderId` - It's return the id of created folder.\
`newFolderName` - It's return the created folder name.\
`rootFolderId` - It's return the root folder id to handle user's activity.

## ✂️ Delete Folder
Using this block you can delete any folder using it's id.

![image](https://user-images.githubusercontent.com/75406851/222395987-a3d82c50-9a52-4369-ae19-e6d9d8476a67.png)

`folderId` - Enter folder id.

![image](https://user-images.githubusercontent.com/75406851/222396015-dec529a9-ac1a-428f-9ea3-5b0039972f2e.png)

`folderId` - It's return the id of deleted folder.\
`isDeleted` - It's return boolean.

## ⬇️ Get Folders
Using this block you can get folders from your drive root folder.

![image](https://user-images.githubusercontent.com/75406851/222396058-14a33a20-ce55-4cc8-803b-4db57ee039a3.png)

`rootFolderId` - Enter root folder id.

![image](https://user-images.githubusercontent.com/75406851/222396086-0c5b7c59-ccb5-4cae-ba10-53e30bfc6aa1.png)

`rootFolderId`> - It's return the id of root folder.\
`folderIds` - It's return the list of folders ids.\
`folderNames` - It's return the list of folders names.\
`folderSizes` - It's return the list of folders sizes.

## ✍️ Rename Folder
Using this block you can rename your folder name.

![image](https://user-images.githubusercontent.com/75406851/222396168-f6bfb401-f588-444a-9678-1dd141b1d791.png)

`folderId` - Enter folder id.\
`new Name` - Enter new name.

![image](https://user-images.githubusercontent.com/75406851/222396191-37aeede3-d262-4e9a-8d74-baf57e707cc9.png)

`folderId` - It's return the id of folder.\
`folderName` - It's return the new name of folder.

## 🗃️ Move File
Using this block you can move file from one folder to another folder.

![image](https://user-images.githubusercontent.com/75406851/222396234-8d18c10f-a225-42ec-8d15-84fc8da46695.png)

`folderId` - Enter folder id where you want to move your file.\
`fileId` - Enter file id.

![image](https://user-images.githubusercontent.com/75406851/222396258-8de72ba6-9f9f-43bd-bfdc-7dc9021557b7.png)

`folderId` - It's return the id of folder.\
`fileId` - It's return the id of file.

## 📁 Move Folder
Using this block you can move your folder to another folder.

![image](https://user-images.githubusercontent.com/75406851/222396346-5f069124-fc9e-49f2-9d33-a91f4b5352e4.png)

`rootFolderId` - Enter root folder id.\
`childFolderId` - Enter child folder id.

![image](https://user-images.githubusercontent.com/75406851/222396386-871e6e4b-d00c-4e56-9b34-78f15ef20a67.png)

`rootFolderId` - It's return the id of root folder.\
`childFolderId` - It's return the id of child folder.

## 🔐 Encode & Decode
Using this block you can protect your folder ids. Set level (1-100) and password length must be 5 or more.

<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/75406851/222396452-8fdbdf51-a5b5-4b05-a8f5-c93b4db770d3.png"></td>
    <td><img src="https://user-images.githubusercontent.com/75406851/222396477-0d1d2f40-0aca-457c-828f-1c2fec921b85.png"></td>
  </tr>
</table>

## ❌ Failed
It rises if got any error. Check function name to understand that error is from where and read error message to understand the reason.

![image](https://user-images.githubusercontent.com/75406851/222396553-a45e5a37-bc3d-458f-8712-e0e09ec048a7.png)

`function Name` - It's return the function name which function got the error.\
`error Message` - It's return the error message.

## 📝 Release Notes ↷
<li><b>7.0.0:</b>  Added <ins>CapturePhotoToUpload</ins> function. Now you can take photo using camera to upload taken image into Drive folder. Also you can compress image size before upload. <sub>(I'll charge small amount to receive this update for paid users.)</sub>
<li><b>6.0.0:</b> Added <ins>UploadMultipleFiles</ins> function. Now you can upload multiple files in single request.
<br>Added <ins>UploadFileByUrl</ins> function. Now you can upload file into drive from internet.
<br>Added <ins>UploadMultipleFilesByUrl</ins> function. Now you can upload multiple files from internet in a single request.
<br>Added <ins>UpdateFile</ins> function. Now you can update that file which already exist into your drive.
<li><b>5.9.1:</b> Update for Support Android 11+ devices.

## 🗒️Extension specifications:
<img src="https://github.com/jewelshkjony/GoogleDrive/raw/main/images/download.png"/> <a href="https://t.me/jewelshkjony">com.jewel.googledrive.aix</a> (91.4 KB) \
<b>Version:</b> 7.0.0\
<b>Price:</b> $10 USD (Standard Edition) - <sub>You'll not get next updates are free. You've to pay again. Also It has validity limitation.</sub>\
<b>Price:</b> $20 USD (Premium Edition) - <sub>Available to get futures updates for free. No limitation remain.</sub>\
<b>Price:</b> $30 USD (Custom Edition) - <sub>More secure and more faster. Also you can order me to customize this extension for your need.</sub>\
<b>Last amendment:</b> 10 March 2023\
<b>Supported builder:</b> <a href="https://www.kodular.io/">Kodular</a>, <a href="https://niotron.com/">Niotron</a>, <a href="https://appzard.com/">AppZard</a>, <a href="https://androidbuilder.in/">AndroidBuilder</a>, <a href="http://ai2.appinventor.mit.edu/">App Inventor</a> and it's other distributions.

## 📫 How to reach me -

<a href="https://t.me/jewelshkjony">Telegram</a> | <a href="https://wa.me/8801775668913">WhatsApp</a> | <a href="https://fb.com/jewelshkjony">Facebook</a> | <a href="https://m.me/jewelshkjony">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony">Youtube</a>

## 💲 Payment Methods ↓

❏ <a href="https://www.xoom.com/bangladesh/send-money" target="_blank">Xoom</a> | <a href="https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=20" target="_blank">Wise</a> | <a href="https://www.skrill.com/en/">Skrill</a> | <a href="https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV" target="_blank">Binance</a> | <a href="https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me">Pay2Me</a> | <b>Paypal</b> (Global)

❏ <a href="https://bka.sh/next?c=signup&uuid=C1CC9JVT1" target="_blank">bkash</a> | <a href="https://play.google.com/store/apps/details?id=com.konasl.nagad">Nagad</a> | <a href="https://play.google.com/store/apps/details?id=com.dbbl.mbs.apps.main">Rocket</a> (Bangladesh)
