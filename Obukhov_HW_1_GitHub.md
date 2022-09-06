### GIT Homework 1

*Для выполнения задания у вас должен быть установлен GitBash для Windows.
Создан аккаунт в GitHub.*

*Все шаги сценария выполняйте в терминале GitBash, Terminal, в папке под гитом.*

*Как отправить ДЗ на проверку.*

* **1.** *Создайте текстоовый файл, как в первом ДЗ по Terminal.*

* **2.** *Сценарий перенесите в этот файл.*
 
* **3.** *Напротив каждого действия напишите команду в GitBash.*

*Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.*
___
## JSON - https://github.com/Sapphireexe/JSON
___
**4.** Создать внешний репозиторий c названием *JSON*.
>https://github.com/new => Repository name => JSON => Add a README file => Create

 **5.** Клонировать репозиторий *JSON* на локальный компьютер.
```
$ git clone https://github.com/Sapphireexe/JSON.git
```
 **6.** Внутри локального *JSON* создать файл “`new.json`”.
```
$ cd JSON/
$ touch new.json
```
 **7.** Добавить файл под гит.
 ```
$ git status
$ git add new.json
$ git status
```
 **8.** Закоммитить файл.
 ```
$ git commit -m "Add new.json"
```
 **9.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **10.** Отредактировать содержание файла “`new.json`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *JSON*.
```
$ vim new.json
```   
>===> INSERT ===>
```
{
        "p1":"Obukhov Anatoliy Evgenievich",
        "p2":"33",
        "p3":"4",
        "p4":"1000"
}
```
>===> Esc ===> :wq

 **11.** Отправить изменения на внешний репозиторий.
 ```
$ git commit -am "added info to new.json"
$ git push
```
 **12.** Создать файл `preferences.json`.
 ```
$ cat > preferences.json
```
>Ctrl+C

 **13.** В файл `preferences.json` добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить*) в формате *JSON*.
 ```
$ vim preferences.json
```
>===> INSERT ===>
```
{
	"p1":"A.I. Artificial Intelligence",
	"p2":"The Mandalorian",
	"p3":"Chocolate",
	"p4":"Autumn",
	"p5":"Norway"
}
```
>===> Esc ===> :wq

 **14.** Создать файл `sklls.json` добавить информацию о скиллах которые будут изучены на курсе в формате *JSON*
 ```
$ touch skills.json
$ vim skills.json
```
>===> INSERT ===>
```
{
        "p1":"Linux Terminal",
        "p2":"JavaScript",
        "p3":"Postman",
        "p4":"SQL",
        "p5":"Android Studio",
        "p6":"Browser DevTools",
        "p7":"Test design",
        "p8":"Test documentation",
        "p9":"Charles",
        "p10":"Jmeter"
}
```
>===> Esc ===> :wq

 **15.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git add .
$ git commit -m "Added preferences and skills files"
$ git push
```
 **16.** На веб интерфейсе создать файл `bug_report.json`.
>Add file ===> Create new file ===> bug_report.json file name

 **17.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **18.** На веб интерфейсе модифицировать файл `bug_report.json`, добавить баг репорт в формате *JSON*.
>Open file ===> Edit file ===>
```
{
  "p1":"Bug_ID",
  "p2":"Summary",
  "p3":"Version_number",
  "p4":"Severity",
  "p5":"Priority",
  "p6":"Author",
  "p7":"Assigned to",
  "p8":"Environment",
  "p9":"Steps",
  "p10":"Actual_result",
  "p11":"Expected_result",
  "p12":"Attachments"
}
```
 **19.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **20.** Синхронизировать внешний и локальный репозиторий *JSON*
 ```
$ git fetch
$ git pull
$ git fetch
```
___
## XML - https://github.com/Sapphireexe/XML
___
 **21.** Создать внешний репозиторий c названием *XML*.
>https://github.com/new => Repository name => XML => Add a README file => Create

 **22.** Клонировать репозиторий *XML* на локальный компьютер.
 ```
$ cd ..
$ git clone https://github.com/Sapphireexe/XML.git
$ cd XML/
```
 **23.** Внутри локального *XML* создать файл “`new.xml`”.
 ```
$ touch new.xml
```
 **24.** Добавить файл под гит.
 ```
$ git add new.xml
```
 **25.** Закоммитить файл.
 ```
$ git commit -m "created new.xml"
```
 **26.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **27.** Отредактировать содержание файла “`new.xml`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *XML*.
 ```
$ vim new.xml
```
>===> INSERT ===>
```
<xml>
        <p1>"Obukhov Anatoliy Evgenievich"</p1>
        <p2>"33"</p2>
        <p3>"4"</p3>
        <p4>"1000"</p4>
```
>===> Esc ===> :wq

 **28.** Отправить изменения на внешний репозиторий.
 ```
$ git commit -am "Added info to new.xml"
$ git push
```
 **29.** Создать файл `preferences.xml`
 ```
$ touch preferences.xml
```
 **30.** В файл `preferences.xml` добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить*) в формате *XML*.
 ```
$ vim preferences.xml
```
>===> INSERT ===>
```
<xml>
	<p1>"A.I. Artificial Intelligence"</p1>
	<p2>"The Mandalorian"</p2>
	<p3>"Chocolate"</p3>
	<p4>"Autumn"</p4>
	<p5>"Norway</p5>
```
>===> Esc ===> :wq

 **31.** Создать файл `sklls.xml` добавить информацию о скиллах которые будут изучены на курсе в формате *XML*
 ```
$ cat > skills.xml
```
>Ctrl+C
```
$ vim skills.xml
```
>   ===> INSERT ===>
```
<xml>
        <p1>"Linux Terminal"</p1>
        <p2>"JavaScript"</p2>
        <p3>"Postman"</p3>
        <p4>"SQL"</p4>
        <p5>"Android Studio"</p5>
        <p6>"Browser DevTools"</p6>
        <p7>"Test design"</p7>
        <p8>"Test documentation"</p8>
        <p9>"Charles"</p9>
        <p10>"Jmeter"</p10>
```
>===> Esc ===> :wq

 **32.** Сделать коммит в одну строку.
 ```
$ git add .; git commit -m "Added preferences and skills files"
```
 **33.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git push
```
 **34.** На веб интерфейсе создать файл `bug_report.xml`.
 >Add file ===> Create new file ===> bug_report.xml file name

 **35.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **36.** На веб интерфейсе модифицировать файл `bug_report.xml`, добавить баг репорт в формате *XML*.
>Open file ===> Edit file ===>
```
<xml>
  <p1>"Bug_ID"</p1>
  <p2>"Summary"</p2>
  <p3>"Version_number"</p3>
  <p4>"Severity"</p4>
  <p5>"Priority"</p5>
  <p6>"Author"</p6>
  <p7>"Assigned to"</p7>
  <p8>"Environment"</p8>
  <p9>"Steps"</p9>
  <p10>"Actual_result"</p10>
  <p11>"Expected_result"</p11>
  <p12>"Attachments"</p12>
  ```
 **37.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **38.** Синхронизировать внешний и локальный репозиторий *XML*
 ```
$ git fetch
$ git pull
$ git fetch
```
___
## TXT - https://github.com/Sapphireexe/TXT
___
 **1.** Создать внешний репозиторий c названием *TXT*.
>https://github.com/new => Repository name => TXT => Add a README file => Create

 **2.** Клонировать репозиторий *TXT* на локальный компьютер.
 ```
$ cd ..
$ git clone https://github.com/Sapphireexe/TXT.git
```
 **3.** Внутри локального *TXT* создать файл “`new.txt`”.
 ```
$ cd TXT/
$ touch new.txt
```
 **4.** Добавить файл под гит.
 ```
$ git add new.txt
```
 **5.** Закоммитить файл.
 ```
$ git commit -m "Added new.txt"
```
 **6.** Отправить файл на внешний GitHub репозиторий.
 ```
$ git push
```
 **7.** Отредактировать содержание файла “`new.txt`” - написать информацию о себе (*ФИО, возраст, количество домашних животных, будущая желаемая зарплата*). Всё написать в формате *TXT*.
 ```
$ vim new.txt
```
>   ===> INSERT ===>
```
1) Obukhov Anatoliy Evgenievich
2) 33
3) 4
4) 1000
```
>===> Esc ===> :wq

 **8.** Отправить изменения на внешний репозиторий.
 ```
$ git commit -am "Added info to new.txt"
$ git push
```
 **9.** Создать файл `preferences.txt`
 ```
$ touch preferences.txt
```
 **10.** В файл `preferences.txt`” добавить информацию о своих предпочтениях (*Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить*) в формате *TXT*.
 ```
$ vim preferences.txt
```
>   ===> INSERT ===>
```
1) A.I. Artificial Intelligence
2) The Mandalorian
3) Chocolate
4) Autumn
5) Norway
```
>===> Esc ===> :wq

 **11.** Создать файл `sklls.txt` добавить информацию о скиллах которые будут изучены на курсе в формате *TXT*
 ```
$ cat > skills.txt <<EOF
1) Linux Terminal
2) JavaScript
3) Postman
4) SQL
5) Android Studio
6) Browser DevTools
7) Test design
8) Test documentation
9) Charles
10) Jmeter
EOF
```
 **12.** Сделать коммит в одну строку.
 ```
$ git add .; git commit -m "Added preferences and skills files"
```
 **13.** Отправить сразу 2 файла на внешний репозиторий.
 ```
$ git push
```
 **14.** На веб интерфейсе создать файл `bug_report.txt`.
>Add file ===> Create new file ===> bug_report.txt file name

 **15.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Created bug_report file ===> Commit changes

 **16.** На веб интерфейсе модифицировать файл `bug_report.txt`, добавить баг репорт в формате *TXT*.
>Open file ===> Edit file ===>
```
1) Bug_ID
2) Summary
3) Version_number
4) Severity
5) Priority
6) Author
7) Assigned to
8) Environment
9) Steps
10) Actual_result
11) Expected_result
12) Attachments
```
 **17.** Сделать *Commit changes* (сохранить) изменения на веб интерфейсе.
>Added bug_report structure ===> Commit changes

 **18.** Синхронизировать внешний и локальный репозиторий *TXT*
 ```
$ git fetch
$ git pull
$ git fetch
```
___
