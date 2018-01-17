# Angular2-Read-CSV-File
Sample Angular2 app to Read .csv file in Angular2. Application read, parse and display csv file contents using Angular2.


Sample application features:
1. It provides configurable on/off validations feature as shown below.

```
export class Constants {
    static tokenDelimeter = ",";
    static isHeaderPresentFlag = true;
    static validateHeaderAndRecordLengthFlag = true;
    static valildateFileExtenstionFlag = true;
}
```
STEP 1:  
Download the sample application.

STEP 2:  
Open command prompt, navigate to application folder and run "npm install" command.


(This step will download all development dependencies. It may take some time to dowload all dependencies. if you face any issue while downloading, open the command prompt as "Run as Administrator" and then execute "npm install")

STEP 3:  
Open command prompt, navigate to application folder and run "npm run server" command.
This step will start the server. 

STEP 4: 
After server starts, start the application by hitting "http://localhost:8080/" in browser.

STEP 5: 
Application will get started and you can play with application by importing sample csv files present along with bundle.
