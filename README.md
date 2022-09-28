gdrive
======


## Overview
gdrive is a command line utility for interacting with Google Drive.

## Important

1. Enable https://console.cloud.google.com/marketplace/product/google/drive.googleapis.com
2. https://console.cloud.google.com/apis/credentials and application type to be Desktop App give some name
3. In "OAuth consent screen", set Publishing status to Testing; User type to External; In "Test users" add your email address.
4. Get the values for `clientId` and `clientSecret`


## Edit and compile

1. Just edit the `clientId` and `clientSecret` in the file `handlers_drive.go`.
