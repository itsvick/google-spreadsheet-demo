# Google-spreadsheet-demo

google-spreadsheet-demo is the ionic project, which uses google spreadsheet as database.These are the steps for the create google sheet as database.

  - Login with your google account
  - Goto to google [sheets](https://docs.google.com/spreadsheets/u/0/) and click on new sheet
  - Creat your own structured sheet
  - Click on share button and go to advanced link
  - Change access to `public`.
  - Now copy the link and get unique-ID of the spreadsheet only. For example- https://docs.google.com/spreadsheets/d/1ZNUGmH_rL4UOQc1L-ejd-RkyL5cC0WqSTBkiM2S5iKk/edit?usp=sharing from which key is `1ZNUGmH_rL4UOQc1L-ejd-RkyL5cC0WqSTBkiM2S5iKk` save it somewhere.
  - Use google script url for converting this spreadsheet data to the `JSON`data link- https://script.google.com/macros/s/AKfycbz29458e0j1syowvR2jCmNN1kLOAaCG7Sm7Qd6qrOKfQs4yX3v6/exec?id=SheetID&sheet=Sheet1
 edit above link- add your sheetID we saved in to the SheetID place and make sure that you have mentioned the sheet name in the last.
  - Now final link is here-https://script.googleusercontent.com/macros/echo?user_content_key=slEel99gkNDp84RKKoq21rMZH53Ub09v0yjAOpXRRH5bgg09D0KDIhf0SzLp9bItSWVWhE31mj4OzAjEZl4quo_VZ_OwRcKcOJmA1Yb3SEsKFZqtv3DaNYcMrmhZHmUMWojr9NvTBuBLhyHCd5hHa62MuRIn2j5QbUzniW0sf06jnq_Ay3QVlLuOyaHCp5SMwRiHnxlG9e9vT7K2vRYzpbC7lNum4H1JN7t35d6mzdFfw2gIKAgLHKmKoZoFT8DjWFGpEDgtJa6WURRAzLVRWO2bxv-WHbcc5y7FLqOV0Tk27B8Rh4QJTQ&lib=Mu_7H1n57aUJw8R0L50Ok_4igttXMoMPk 
  which contains world country data.

# Gets started with app!!!

  - You dont need to create new project just clone this project
  - Fire this command (Assuming you have already installed npm, ionic and cordova)
```sh
$ npm install
$ ionic platform add android
$ ionic run android
```

Now you all have done!!!
Enjoy Coding :)

License
----

MIT


**Free Software, Hell Yeah!**
