## My Hospital Api
## https://github.com/Harshvardhanshinde14 created by Harshvardhan Shinde.

## Theme
    I designed Hospital api for the doctors of Hospitals which have been alloted for testing purposes of COVID+

    . There can be two types of users 
    . Doctors
    . Patient
    . Doctors would register
    . Doctors would login
    . each time patients visit doctor would do two steps
    . Register the patient in the app 
    . After the checkup, create a Report
    . Patient Report will have the following fields
    . Created by doctor
    . Status
    . Can be either of: [Negative,
     Travelled-Quarantine, Symptoms-Quarantine, Positive-Admit] from the qn documentation


## Prerequisites
    1 Node.js
    2 Git


## Tech Used
    1 mongoose.js
    2 jwt
    3 passport
    4 passport-local


### install the npm first
`npm install`
### start the server
`npm start`

### This is my doctors register
![Alt text](images/01.png)


### This is my doctor login
![Alt text](images/02.png)

### This is my patients register
![Alt text](images/03.jpeg)

### This is my patients create_report
![Alt text](images/04.jpeg)

### This is my patients all_reports
![Alt text](images/05.jpeg)

### Note:: I have checked the given api and upload and attached it to my images folder as well 

## Folder Structure

| --- .vscode<br>
| ---   config<br>
| ---    | -- middleware <br>
| ---    | -- mongoose <br>
| ---    | -- passport_jwt_strategy<br>
| ---    controllers<br>
| ---    | -- api<br>
| ---    | -- | -- v1<br>
| ---    | -- | -- | -- doctor_controller<br>
| ---    | -- | -- | -- patient_controller<br>
| ---    | -- | -- | -- report_controller<br>
| ---    images<br>
| ---     models<br>
| ---     | -- doctor<br>
| ---     | -- patient<br>
| ---     | -- report<br>
| ---     routes<br>
| ---     | --api<br>
| ---     | --| -- v1<br>
| ---     | --| --  | --- doctors<br>
| ---     | --| --  | --- index<br>
| ---     | --| --  | --- patients<br>
| ---     | --| --  | --- reports<br>
| ---     | --| -- index<br>
| ---     | -- index<br> 
| ---     .gitignore<br>
| ---      index<br>
| ---      package-lock.json<br>
| ---      package.json<br>
| ---      Readme.md<br>

  
