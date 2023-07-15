## Homework #2

### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bug_Reports
- SQL
- Charles
- Mobile_Testing

`git branch Postman`

и т.д. Название ветки должно быть без пробелов. Создать несколько веток в одной команде можно через `&&`

### 2. Запушить все ветки на внешний репозиторий

`git push -u origin Postman`

и т.д.

### 3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта
```
git checkout Bug_Reports
vim bug_report.txt
```
### 4. Запушить структуру багрепорта на внешний репозиторий
```
git add bug_report.txt
git commit -m "first"
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
