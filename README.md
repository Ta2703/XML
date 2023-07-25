 21. Создать внешний репозиторий c названием XML.
```
XML - Repositories - NEW - JSON - like [Add a README file] - Create repository
```
 22. Клонировать репозиторий XML на локальный компьютер.
```
git clone https://github.com/Ta2703/XML.git
```
 23. Внутри локального XML создать файл “new.xml”.
```
cd XML && touch new.xml
```
 24. Добавить файл под гит.
```
git add new.xml
```
 25. Закоммитить файл.
```
git commit -a -m "created the new.xml"
```
 26. Отправить файл на внешний GitHub репозиторий.
```
git push origin main
```
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
 vim new.xml   
[i]
```
```
<?xml version="1.0"?>
<GPS_Storage xmlns:xsi="http://www.w3.org/2001/XMLSchemainstance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
<AboutMe>
<Name>Tamara</Name>
<Age>28</Age>
<Animal>1</Animal>
<Salary>500$</Salary>
</AboutMe>
  ```

```
[esc] :wq
```

 28. Отправить изменения на внешний репозиторий.
```
git commit -a -m "edited the new.xml" && git push origin main
```
29. Создать файл preferences.xml
```
touch preferences.xml
```
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
vim preferences.xml
[i]
```
```
<?xml version="1.0"?>
<GPS_Storage xmlns:xsi="http://www.w3.org/2001/XMLSchemainstance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
<AboutMe>
<FavoriteFilm>Titanic</FavoriteFilm>
<FavoriteSeries>Black mirror</FavoriteSeries>
<FavoriteFood>Bananas</FavoriteFood>
<FavoriteTime>Spring</FavoriteTime>
<FavoriteSide>Spain</FavoriteSide>
</AboutMe>
```
  
  ```
[esc] :wq
```
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
touch skills.xml 
vim skills.xml 
[i]
```

```
<?xml version="1.0" encoding="UTF-8" ?>
<AboutSkills>
    <HardSkills><Skills>Basic theory (What is testing, bug reports, documentation, types, methods, testing areas, etc.) SDLC, STLC.</Skills></HardSkills>
    <HardSkills><Skills>What is a client-server architecture.</Skills></HardSkills>
    <HardSkills><Skills>HTTP Methods of requests to the server.</Skills></HardSkills>
    <HardSkills><Skills>HTTP server response codes.</Skills></HardSkills>
    <HardSkills><Skills>Structures of HTTP requests and responses.</Skills></HardSkills>
    <HardSkills><Skills>What is JSON, XML. Their structure.</Skills></HardSkills>
    <HardSkills><Skills>API testing via Postman (JS, API autotests).</Skills></HardSkills>
    <HardSkills><Skills>Removing and reading logs from an external server.</Skills></HardSkills>
    <HardSkills><Skills>Sniffing http web traffic via Charles and Fiddler.</Skills></HardSkills>
    <HardSkills><Skills>Dev Tools of web browsers (Google Chrome, FireFox).</Skills></HardSkills>
    <HardSkills><Skills>VPN. (How it works, why you need it, how to use it, tool options)</Skills></HardSkills>
    <HardSkills><Skills>Mobile testing.</Skills></HardSkills>
    <HardSkills><Skills>Feature iOS, Android, guidelines.</Skills></HardSkills>
    <HardSkills><Skills>Building iOS applications on XCode. (Those who do not have a Mac computer, just look)</Skills></HardSkills>
    <HardSkills><Skills>Building Android applications on Android Studio.</Skills></HardSkills>
    <HardSkills><Skills>ADB (android device management).</Skills></HardSkills>
    <HardSkills><Skills>Setting up proxy and vpn on iOS and Android.</Skills></HardSkills>
    <HardSkills><Skills>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android.</Skills></HardSkills>
    <HardSkills><Skills>Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)</Skills></HardSkills>
    <HardSkills><Skills>Basics of bash scripting, automation of routine tasks on the server.</Skills></HardSkills>
    <HardSkills><Skills>Access to remote servers.</Skills></HardSkills>
    <HardSkills><Skills>SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</Skills></HardSkills>
    <HardSkills><Skills>Postgres database (installation, configuration and use).</Skills></HardSkills>
    <HardSkills><Skills>Non-relational database Redis (installation, configuration and use).</Skills></HardSkills>
    <HardSkills><Skills>Load testing in Jmeter.</Skills></HardSkills>
    <HardSkills><Skills>Scrum development methodology.</Skills></HardSkills>
    <HardSkills><Skills>Test Design Techniques (Equivalence Classes, Boundary Values, Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice), States and Transitions)</Skills></HardSkills>
    <HardSkills><Skills>Python. (Learning the basics. Creating a client-server application)</Skills></HardSkills>
</AboutSkills>
```
```
[esc] :wq
```

 32. Сделать коммит в одну строку.
```
git add . && git commit -m "Correction of two files"
```
 33. Отправить сразу 2 файла на внешний репозиторий.
```
git push origin main
```
 34. На веб интерфейсе создать файл bug_report.xml.
```
add file / create new file
```
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
«bug_report.xm»/ Commit changes
```
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```
 bug_report.xml / Edit this file 
```
```
<?xml version="1.0" encoding="UTF-8" ?>
<dataset>
    <record><success>user</success><true>[object Object]</true></record>
</dataset>
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 38. Синхронизировать внешний и локальный репозиторий XML
```
git pull origin main
```
