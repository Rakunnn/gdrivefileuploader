# Gdrivefileuploader

## For lazy persons.

This project is intended for on the fly backup of files.
Recommended when using crontab.

First enable [google drive api](https://developers.google.com/drive/api/v3/enable-drive-api),it will show steps to enable the API.
Go to [developer console](https://console.developers.google.com) and search for 'APIs and Services',then create project.
```
Acquire secret:
   1.'Credentials',click "CREATE CREDENTIALS"
   2.SELECT "OATH client ID"
   3. Select Application type as "DESKTOP APP"
   4. rename the oauth client then click create.
   5.Download the client_id then put to the folder where the python scripts location.
   6.Check the name of the client id json file to "client_secrets"
   Install PyDrive (pip install PyDrive)
```

