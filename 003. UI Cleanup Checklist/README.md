# UI Cleanup Checklist

## There are two main goals for this Cleanup task:
### 1. On codes level, pass EsLint check to guarantee our codes meet the React15 code standards
### 2. On runtime level, make sure there's no errors on every page
<!-- TOC -->
## Eslint CheckList - Code level
- [1.initial action](#1-initial-action)
- [2.common rules](#2-common-rules)
  - [2.1 remove unused imports](#2.1-remove-unused-imports)
<!-- /TOC -->

# 1. Initial Action
* Once open the file, it should be like this: 
* ![initialFile](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/initialFile.JPG)
* PROBLEMS tag shows the number for issues not pass ES code standards.We can see there are 201 problems now.
* ACTIONS: save file muntiple of times, until the number of problems not change any more. Then we can go to next steps. Screen should be like below now.
* ![initialSavedFile](https://github.com/ebaotech-oss/vault-claim-documentation/blob/master/003.%20UI%20Cleanup%20Checklist/Images/initialSavedFile.JPG)
# 2. Common Rules
## 2.1 Remove unused imports
* Imports that not used will be displayed in gray. Fix this by deleting all the unused imports.
