## Homework #2

### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug_Reports
- SQL
- Charles
- Mobile_Testing

`git branch Postman` и т.д. 

Название ветки должно быть без пробелов. Создать несколько веток одной командой можно через `&&`

### 2. Запушить все ветки на внешний репозиторий

`git push -u origin Postman` и т.д.

### 3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта
```
git checkout Bug_Reports
vim bug_report.txt
```

Далее в режиме редактирования добавляем информацию:
```
Title: 

Precondition: 

Steps to reproduce:
1. 
2.
3.

Expected result: 

Actual result: 

Severity: 

Environment: 

Attachments: 
```

### 4. Запушить структуру багрепорта на внешний репозиторий
```
git add bug_report.txt
git commit -m "first commit"
git push
```
### 5. Вмержить ветку Bug_Reports в Main
```
git checkout main
git merge Bug_Reports
```
### 6. Запушить main на внешний репозиторий

`git push`

### 7. В ветке CheckLists набросать структуру чек листа
```
git checkout Checklists
vim checklist.txt
```

Далее в режиме редактирования добавляем информацию:
```
project
date
tester
environment

check					  status

1. check logo				  passed
2. check burger menu			  passed
3. check login button			  passed
4. login with valid credentials		  passed
5. login with invalid credentials	  passed
6. check forgot password		  failed
7. check privacy policy			  passed
8. check footer				  passed
```
### 8. Запушить структуру на внешний репозиторий
```
git add checklist.txt
git commit -m "checklist"
git push
```
### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

- открыть на GitHub удалённый репозиторий
- выбрать ветку Checklists
- кликнуть [Compare & pull request]
- в поле "Commit Message" ввести какое-нибудь сообщение или оставить сообщение по умолчанию
- кликнуть [Create pull request]
- кликнуть [Merge pull request]
- кликнуть [Confirm merge]

### 10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git pull
```
