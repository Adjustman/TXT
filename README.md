# TXT

GIT Homework 1

JSON

 4. Создать внешний репозиторий c названием JSON  

	* переходим на сайт github.com
	* заходим на вкладку "Repositories"
	* создаем репозиторий, нажав на кнопку "New"
	* в параметрах нужно указать: 
		- имя репозитория 
		- доступность(публичный или приватный)
		- добавить ли файл README.md (в нем можно/нужно ввести описание данного репозитория)
		- добавить игнор лист(шаблон/стоп-лист, который позволяет 'отсекать' файлы, которые не нужно синхронизировать с репозиторием

 5. Клонировать репозиторий JSON на локальный компьютер

	git clone <название репозитория> 
	git clone https://github.com/Adjustman/JSON.git

 6. Внутри локального JSON создать файл “new.json”

	cat > new.json

 7. Добавить файл под гит

	git add new.json

 8. Закоммитить файл.

	git commit -m "add new.json"

 9. Отправить файл на внешний GitHub репозиторий.

	git push
 
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

	Json-объект — это неупорядоченное множество пар «ключ:значение», заключённое в фигурные скобки «{ }». Ключ описывается строкой, между ним и значением стоит символ «:». Пары ключ-значение отделяются друг от друга запятыми.

	{
    	"name": "Savchenko Dmitry Yurievich",
    	"age": 36,
    	"pets": null,
    	"future desired salary": 500
	}

 12. Создать файл preferences.json

	cat > preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, 	любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	
	В любом текстовом редакторе вносим данные и сохраняем
	
	{
    "favorite movie": "Snatch",
    "favorite series": "Black mirror",
    "favorite food": "B-B-Q",
    "favorite season": "spring",
    "country you would like to visit": "Dominican Republic"
	}

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
	
	cat >> sklls.json

	{
    "base theory":  [
        "SDLC",
        "STLC"      ],
    "sniffing":     [
        "Charles",
        "Fiddler"   ],
    "Linux": "terminal",
    "SQL Basics": [
        "Create",
        "Delete"  
        "Drop"
        "Insert Into"
        "Select" ],
    "Stress Testing": "Jmeter"
    
  }

 15. Отправить сразу 2 файла на внешний репозиторий.

	git add preferences.json skills.json
	git commit -a -m "add preferences.json and skills.json"	
	git push

 16. На веб интерфейсе создать файл bug_report.json

	В веб интерфейсе внутри репозитория нажимаем
		
		* "Add file"
		* "Create new file"
		
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

		* Нажать "Commit changes"
 
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

	* Выбрать файл
	* Нажать "Edit this file"	
	* Внести изменения

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	* Нажать "Commit changes"

 20. Синхронизировать внешний и локальный репозиторий JSON

	git fetch
	git pull
	


XML

 21. Создать внешний репозиторий c названием XML

	* переходим на сайт github.com
	* заходим на вкладку "Repositories"
	* создаем репозиторий, нажав на кнопку "New"
	* в параметрах нужно указать: 
		- имя репозитория <XML>
		- доступность(публичный или приватный)
		- добавить ли файл README.md (в нем можно/нужно ввести описание данного репозитория)
		- добавить игнор лист(шаблон/стоп-лист, который позволяет 'отсекать' файлы, которые не нужно 		  синхронизировать с репозиторием
	
 22. Клонировать репозиторий XML на локальный компьютер.

	git clone <ссылка на репозиторий>
	git clone https://github.com/Adjustman/XML.git	

 23. Внутри локального XML создать файл “new.xml”.

	cat > new.xml

 24. Добавить файл под гит.

	git add new.xml

 25. Закоммитить файл.

	git commit -m "add new.xml"

 26. Отправить файл на внешний GitHub репозиторий.

	git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

	В любом текстовом редакторе вносим данные в формате XML и сохраняем

	<?xml version="1.0" encoding="windows-1251"?>
	<note>
   		<full name>Savchenko Dmitry Yurievich</full name>
   		<age>36</age>
   		<number of pets>null</number of pets>
   		<future desired salary>500</future desired salary>
	</note>

 28. Отправить изменения на внешний репозиторий.

	git add new.xml
	git commit -m "add info to new.xml"
	git push
 
 29. Создать файл preferences.xml

	cat > preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

	В любом текстовом редакторе вносим данные в формате XML и сохраняем
	
<?xml version="1.0" encoding="windows-1251"?>
<note>
   <favorite movie>Snatch</favorite movie>
   <favorite series>Black mirror</favorite series>
   <favorite food>B-B-Q</favorite food>
   <favorite season>spring</favorite season>
   <country you would like to visit>Dominican Republic</country you would like to visit>
</note>
		

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

	cat >> skills.xml

	<?xml version="1.0" encoding="windows-1251"?>
	<note>
   		<base theory>SDLC_STLC</base theory>
   		<sniffing>Charles_Fiddler</sniffing>
   		<Linux>Terminal</Linux>
   		<SQL Basics>Create_Delete_Select</SQL Basics>
	</note>

 32. Сделать коммит в одну строку

	git add . && git commit -m "one line commit"

 33. Отправить сразу 2 файла на внешний репозиторий.

		git push

 34. На веб интерфейсе создать файл bug_report.xml.
	
	В веб интерфейсе внутри репозитория нажимаем
		
		* "Add file"
		* "Create new file"

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	* Нажать "Commit changes"

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

	* Выбрать файл
	* Нажать "Edit this file"	
	* Внести изменения

	<?xml version="1.0" encoding="windows-1251"?>
		<bug_report>
   			<ID>br-00155</ID>
   			<Summary>Charles_Fiddler</Summary>
   			<Steps_to_reproduce>1-2-3-4</Steps_to_reproduce>
      			<Actual_result>The words on the page are not translated</Actual_result>
      			<Expected_Result>The words on the page are translated</Expected_Result>
      			<Severity>Minor</Severity>
      			<Priority>low</Priority>
      			<Attachments>URL to attachments</Attachments>
      			<Additional_Information>Terminal</Additional_Information>
		</bug_report>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	* Нажать "Commit changes"
	
 38. Синхронизировать внешний и локальный репозиторий XML

	git fetch
	git pull

TXT

 1. Создать внешний репозиторий c названием TXT.

	* переходим на сайт github.com
	* заходим на вкладку "Repositories"
	* создаем репозиторий, нажав на кнопку "New"
	* в параметрах нужно указать: 
		- имя репозитория <TXT>
		- доступность(публичный или приватный)
		- добавить ли файл README.md (в нем можно/нужно ввести описание данного репозитория)
		- добавить игнор лист(шаблон/стоп-лист, который позволяет 'отсекать' файлы, которые не нужно синхронизировать с репозиторием

 2. Клонировать репозиторий TXT на локальный компьютер.

	git clone <название репозитория> 
	git clone https://github.com/Adjustman/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.

	cat > new.txt

 4. Добавить файл под гит.

	cat > new.txt

 5. Закоммитить файл.

	git commit -m "add new.txt"

 6. Отправить файл на внешний GitHub репозиторий.

	git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

	В любом текстовом редакторе вносим данные и сохраняем
	
	Name - 	Savchenko Dmitry Yurievich
	Age - 	36
	Pets - 	null
	Future desired salary - 500

 8. Отправить изменения на внешний репозиторий.

	git commit -m "add info to new.txt"
	git push

 9. Создать файл preferences.txt
	
	cat > preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

	В любом текстовом редакторе вносим данные и сохраняем

	Favorite movie - Snatch
	Favorite series - Black mirror"
	Favorite food - B-B-Q
	Favorite season - Spring
	Country you would like to visit - Dominican Republic

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

	cat >> skills.txt

	Base theory - SDLC, STLC
	Sniffing - Charles, Fiddler
	Linux - terminal
	SQL Basics - Create, Delete, Drop,Insert Into, Select
	Stress Testing - Jmeter
		*Ctrl+C - сохранить и выйти

 12. Сделать коммит в одну строку.

	git add . && git commit -m "one line commit"

 13. Отправить сразу 2 файла на внешний репозиторий.

	git push
	
 14. На веб интерфейсе создать файл bug_report.txt.

	В веб интерфейсе внутри репозитория нажимаем
		
		* "Add file"
		* "Create new file" - bug_report.txt
		
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	* Нажать "Commit changes"

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

	* Выбрать файл
	* Нажать "Edit this file"	
	* Внести изменения

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	* Нажать "Commit changes"

 18. Синхронизировать внешний и локальный репозиторий TXT

	git fetch
	git pull
