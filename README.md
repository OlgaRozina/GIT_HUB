# This is a part of GIT homework - GIT_HUB
## 1. On the local repository, make branches for:
- Postman
- Jmeter
- CheckList
- Bug Report
- SQL
- Charles
- Mobile testing
```
Create the local repository  > New repository > Create repository
```
####Create branches:
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bug_report re
git branch SQL
git branch Charles
git branch Mobile_testing
```
## 2. Push all branches to the remote repository:
```
git push origin --all
```
***
## 3. In the bug_report branch, create a text document with the structure of a bug report:
```
$ git checkout Bug_report
$ cat>bug_report.txt
ID: 1
Environment: OS = Win_10, Browser = Chrome_112
Summary: 404 error when user is accessing the purchase order report page as a sales manager
Actual result: The report isn't shown as per the criteria selected
Expected result: The report should show as per the criteria selected
Steps to reproduce:
Login as Sales Manager
Go to the Reports page and choose Purchase Order Report
Select any filter criteria
Click the Show Report button
Severity: Medium
Priority: Normal
Reproducibility: Always
Symptom: Missing_feature
Workaround: No
Attachment: Link
Status: Open
Author: Olga_Rozina
Sign to: Olga_Fefilova
```
***
## 4. Push the bug_report structure to the remote repository:
```
git status
git add .
git commit -m "First commit"
git push
```
***
## 5. Merge bug_reports branch into main:
```
git checkout main
git merge Bug_report
```
***
## 6. Push main to the remote repository:
```
$ git push origin main
```
***
## 7. In the checkList branch, create a document with structure of a checklist:
```
$ cat > checklist.txt
    1.Check booking by the registered user;
    2.Check booking by the unregistered user;
    3. Check booking if to enter data yourself in Last Name and First Name fields;
    4. Check booking if to enter data yourself in the Choose reservation and Select table fields;
    5.Check feature select values from the dropdown list in Select table and Choose reservation fields;
    5.Check if the selected place appears in You chose this place field;
    6.Check the ability to confirm the reservation of the selected place;
    7.Check the ability to cancel the reservation of the selected place;
    8. Check if field values are restored after the page restart;
    9. Check if the link works at the selected place;
    10. Check if field values are restored after the page restart;
    11. Check the closure of the form by filling all fields
    12. Check the closure of the form without filling all fields.
```
***
## 8. Push the document to the remote repository:
```
git status
git add .
git commit -m "First commit"
git push
```
***
## 9. Make a Pull Request of the checkList branch in main, on the remote repository:

*Go to the remote repository in the checkList branch > Compare&pull requset*

***
## 10. Synchronize external and local main branches:
```
$ git checkout main
$ git pull
```
***
