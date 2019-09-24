# UI Cleanup Checklist

## There are two main goals for this Cleanup task:
### 1. On codes level, pass EsLint check to guarantee our codes meet the React15 code standards
### 2. On runtime level, make sure there's no errors on every page
<!-- TOC -->
## Eslint CheckList - Code level
- [1.initial action](#1-initial-action)
- [2.common rules](#2-common-rules)
  - [2.1 no-unused-vars](#21-no-unused-vars)
  - [2.2 object-shorthand](#22-object-shorthand)
  - [2.3 no-string-refs](#23-no-string-refs) 
  - [2.4 import/named](#24-import-named)
<!-- /TOC -->

# 1. Initial Action
* Once open the file, it should be like this: 
* ![initialFile](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/initialFile.png)
* PROBLEMS tag shows the number for issues not pass ES code standards.We can see there are 201 problems now.
* ACTIONS: save file muntiple of times, until the number of problems not change any more. Then we can go to next steps. Screen should be like below now.
* ![initialSavedFile](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/initialSavedFile.png)
# 2. Common Rules
## 2.1 no-unused-vars
* unused imports should be deleted.
* ![no-unused-vars](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/no-used-vars.png)
* ACTION: right click on this rule, then click 'delete all unused declarations'
* ![no-unused-vars-action](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/no-used-vars-action.png)
## 2.2 object-shorthand
* ES6 features.
* ![object-shorthand](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/object-shorthand.png)
* ACTION: right click on this rule, then click 'Fix all auto-fixable problems'
* ![object-shorthand-action](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/object-shorthand-action.png)
## 2.3 no-string-refs
* String refs are deprecated. Apply callback pattern instead.
* ![no-string-refs](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/no-string-refs.png)
* ACTION: refactor codes as below.
* ![no-string-refs-action](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/no-string-refs-action.png)
## 2.4 import-named
* The reason for this problem involved is because this import codes are babelified. Hence Eslint cannot find the reference.
* ![import-named](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/import-named.png)
* ACTION: disable this rule in the file.
* ![import-named-action](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/import_named-action.png)
