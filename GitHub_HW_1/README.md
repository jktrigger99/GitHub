## Homework #1

### [JSON](https://github.com/jktrigger99/JSON)

### 1. Создать внешний репозиторий c названием JSON
- открыть GitHub -> Repositories
- кликнуть [New]
- в поле "Repository name" ввести "JSON"
- кликнуть [Create repository]
  
### 2. Клонировать репозиторий JSON на локальный компьютер
- скопировать ссылку на репозиторий
- открыть GitBash и перейти в директорию, куда необходимо клонировать
- `git clone https://github.com/jktrigger99/JSON.git`

### 3. Внутри локального JSON создать файл “new.json”

`touch new.json`

### 4. Добавить файл под гит

`git add .`

### 5. Закоммитить файл

`git commit -m "new.json is added"`

### 6. Отправить файл на внешний GitHub репозиторий

`git push`

### 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON

`vim new.json`
```
{
    "name": "jktrigger",
    "age": 38,
    "pets": 0,
    "desired future salary": 5000
}
```

### 8. Отправить изменения на внешний репозиторий

```
git add .
git commit -m "second commit"
git push
```

### 9. Создать файл preferences.json

`touch preferences.json`

### 10. В файл preferences.json добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON

`vim preferences.json`
```
{
    "Favourite movie": "The Shawshank Redemption",
    "Favourite series": "Better Call Saul",
    "Favourite food": "fried potatoes",
    "Favourite season": "summer",
    "Country I would like to visit": "USA"
}
```

### 11. Создать файл sklls.json и добавить информацию о скиллах, которые будут изучены на курсе в формате JSON

`vim skills.json`
```
{
    "Skills": [
        "Bash commands and simple scripts",
        "Git and GitHub",        
        "Client-server architecture",
				"DevTools",
        "API testing with Postman",
				"SQL",
				"Test design techniques",
        "Writing test documentation",
				"Mobile testing (Android Studio and Xcode)",
        "Charles Proxy and Fiddler",        
        "JMeter" ]
}
```

### 12. Отправить сразу 2 файла на внешний репозиторий

`git add . && git commit -m "third commit" && git push`

### 13. На веб интерфейсе создать файл bug_report.json
- открыть репозиторий
- кликнуть [Add file] -> [Create new file]
- ввести имя
  
### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON

Добавить содержимое:
```
{
  "Title": "(Heisenbug) App Store is opened on any instrument's page when clicking button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)]",
  "Precondition": "the user is authorized",
  "Steps to reproduce": [
    "1. Navigate to capital.com",
    "2. Click menu section [Markets]",
    "3. Scroll down to the widget 'We offer one-click trading experience with 3,700+ world-renowned markets.'", 
    "4. Click on any instrument's link",
    "5. Click button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)]"
  ],
  "Expected result": "Trading Platform is opened",
  "Actual result": "App Store is opened",
  "Severity": "Major",
  "Environment": "Windows 11, Chrome 114",
  "Attachments": "link"
}
```

### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 17. Синхронизировать внешний и локальный репозиторий JSON

`git pull`


### [XML](https://github.com/jktrigger99/XML)

### 1. Создать внешний репозиторий c названием XML
- открыть GitHub -> Repositories
- кликнуть [New]
- в поле "Repository name" ввести "XML"
- кликнуть [Create repository]
  
### 2. Клонировать репозиторий XML на локальный компьютер
- скопировать ссылку на репозиторий
- открыть GitBash и перейти в директорию, куда необходимо клонировать
- `git clone https://github.com/jktrigger99/XML.git`
  
### 3. Внутри локального XML создать файл “new.xml”

`touch new.xml`

### 4. Добавить файл под гит

`git add .`

### 5. Закоммитить файл

`git commit -m "new.xml is added"`

### 6. Отправить файл на внешний GitHub репозиторий

`git push`

### 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML

`vim new.xml`
```
<?xml version="1.0" encoding="UTF-8"?>
<jktrigger>
	<name>jktrigger</name>
	<age>38</age>
	<pets>0</pets>
	<desiredFutureSalary>5000</desiredFutureSalary>
</jktrigger>
```

### 8. Отправить изменения на внешний репозиторий

```
git add .
git commit -m "second commit"
git push
```

### 9. Создать файл preferences.xml

`touch preferences.xml`

### 10. В файл preferences.xml добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате XML

`vim preferences.xml`
```
<?xml version="1.0" encoding="UTF-8"?>
<jktriggerPreferences>
	<FavouriteMovie>The Shawshank Redemption</FavouriteMovie>
	<FavouriteSeries>Better Call Saul</FavouriteSeries>
	<FavouriteFood>fried potatoes</FavouriteFood>
	<FavouriteSeason>summer</FavouriteSeason>
	<СountryIWouldLikeToVisit>USA</СountryIWouldLikeToVisit>
</jktriggerPreferences>
```

### 11. Создать файл sklls.xml и добавить информацию о скиллах, которые будут изучены на курсе в формате XML

`vim skills.xml`
```
<?xml version="1.0" encoding="UTF-8"?>
<AcquiredSkills>
	<skill>Bash commands and simple scripts</skill>
	<skill>Git and GitHub</skill>
	<skill>Client-server architecture</skill>
	<skill>DevTools</skill>
	<skill>API testing with Postman</skill>
	<skill>SQL</skill>
	<skill>Writing test documentation</skill>	
	<skill>Test design technique</skill>	
	<skill>Mobile testing (Xcode and Android Studio)</skill>
	<skill>Charles and Fiddler"</skill>
	<skill>JMeter</skill>
</AcquiredSkills>
```

### 12. Сделать коммит в одну строку

`git add . && git commit -m "third commit"`

### 13. Отправить сразу 2 файла на внешний репозиторий

`git push`

### 14. На веб интерфейсе создать файл bug_report.xml
- открыть репозиторий
- кликнуть [Add file] -> [Create new file]
- ввести имя
  
### 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML

Добавить содержимое:
```
<?xml version="1.0" encoding="UTF-8"?>
<bugReport>
  <Title>(Heisenbug) App Store is opened on any instrument's page when clicking button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)] / [Sell] / [Buy] / [Start Trading] (at the widget "Trading Calculator") / [Trade Now] (at the widget "Single Market")</Title>
  <Precondition>the user is authorized</Precondition>
  <StepsToReproduce>
    <step>1. Navigate to capital.com</step>
    <step>2. Click menu section [Markets]</step>
    <step>3. Scroll down to the widget "We offer one-click trading experience with 3,700+ world-renowned markets."</step>
    <step>4. Click on any instrument's link</step>
    <step>5. Click button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)] / [Sell] / [Buy] / [Start Trading] (at the widget "Trading Calculator") / [Trade Now] (at the widget "Single Market")</step>
  </StepsToReproduce>
  <ExpectedResult>Trading Platform is opened</ExpectedResult>
  <ActualResult>App Store is opened</ActualResult>
  <Severity>Major</Severity>
  <Environment>Windows 11 Chrome 114</Environment>
  <Attachments>link</Attachments>
</bugReport>
```
### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 18. Синхронизировать внешний и локальный репозиторий XML

`git pull`


### [TXT](https://github.com/jktrigger99/TXT)

### 1. Создать внешний репозиторий c названием TXT
- открыть GitHub -> Repositories
- кликнуть [New]
- в поле "Repository name" ввести "TXT"
- кликнуть [Create repository]
  
### 2. Клонировать репозиторий TXT на локальный компьютер
- скопировать ссылку на репозиторий
- открыть GitBash и перейти в директорию, куда необходимо клонировать
- `git clone https://github.com/jktrigger99/TXT.git`

### 3. Внутри локального TXT создать файл “new.txt”

`touch new.txt`

### 4. Добавить файл под гит

`git add .`

### 5. Закоммитить файл

`git commit -m "new.txt is added`

### 6. Отправить файл на внешний GitHub репозиторий

`git push`

### 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT

`vim new.txt`
```
name: jktrigger
age: 38
pets: 0
desired future salary: 5000
```

### 8. Отправить изменения на внешний репозиторий

```
git add .
git commit -m "second commit"
git push
```

### 9. Создать файл preferences.txt

`touch preferences.txt`

### 10. В файл preferences.txt” добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT

`vim preferences.txt`
```
Favourite movie: The Shawshank Redemption
Favourite series: Better Call Saul
Favourite food: fried potatoes
Favourite season: summer
Сountry I would like to visit: USA
```

### 11. Создать файл sklls.txt и добавить информацию о скиллах, которые будут изучены на курсе в формате TXT

`vim skills.txt`
```
Skills:
- Bash commands and simple scripts,
- Git and GitHub,
- Client-server architecture,
- DevTools,
- API testing with Postman,
- SQL,
- Mobile testing (Android Studio and Xcode),
- Charles Proxy and Fiddler",
- JMeter,
- Writing test documentation,
- Test design techniques.
```

### 12. Сделать коммит в одну строку

`git add . && git commit -m "third commit"`

### 13. Отправить сразу 2 файла на внешний репозиторий

`git push`

### 14. На веб интерфейсе создать файл bug_report.txt
- открыть репозиторий
- кликнуть [Add file] -> [Create new file]
- ввести имя

### 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT

Добавить содержимое:
```
Title: 
(Heisenbug) App Store is opened on any instrument's page when clicking button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)] / [Sell] / [Buy] / [Start Trading] (at the widget "Trading Calculator") / [Trade Now] (at the widget "Single Market")

Precondition: the user is authorized

Steps to reproduce:
1. Navigate to capital.com
2. Click menu section [Markets]
3. Scroll down to the widget "We offer one-click trading experience with 3,700+ world-renowned markets." 
4. Click on any instrument's link
5. Click button [Add to Favourite] / [View Detailed Chart] / [Notification (bell)] / [Sell] / [Buy] / [Start Trading] (at the widget "Trading Calculator") / [Trade Now] (at the widget "Single Market")

Expected result: Trading Platform is opened

Actual result: App Store is opened

Severity: Major

Environment: Windows 11, Chrome 114

Attachments: link
```

### 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе

Кликнуть [Commit changes...]

### 18. Синхронизировать внешний и локальный репозиторий TXT

`git pull`
