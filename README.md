 1. Создать внешний репозиторий c названием TXT.
 2. Клонировать репозиторий TXT на локальный компьютер.
 	git clone https://github.com/Strielka/TXT.git
 3. Внутри локального TXT создать файл “new.txt”.
 	cd TXT
 	vim new.txt
 4. Добавить файл под гит.
 	git add new.txt
 5. Закоммитить файл.
 	git commit -m "Lana added new.txt"
 6. Отправить файл на внешний GitHub репозиторий.
 	git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 	vim new.txt
 	My name is Lana, I`m 23 y.o. Living in Ukraine. Have a dog since 2011.
	My future desired salary for a first time - about $500 :)
 8. Отправить изменения на внешний репозиторий.
 	git push
 9. Создать файл preferences.txt
 	vim preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 	vim preferences.txt
 	favourite film - Cyborgs: Heroes Never Die,
    favourite serial - Prison Break,
    favourite food - spagetti,
    favorite season - summer! :),
    country I  would like to visit - Chile, Peru
 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 	vim skills.txt
 	Linux_terminal_(GitBash)_commands, Visual_Studio_Code, JS_functionsm, Chai_JS, Postman, Git_Draw, Git_branch_merge, ClientServer, Postman_scripts_environment, Form_testing, Android studio
 12. Сделать коммит в одну строку.
 	git commit -am "preferences & skills"
 	or   git add . && git commit -m 'Update file'
13. Отправить сразу 2 файла на внешний репозиторий.
	git push
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
	№ 1; 
	Bug summary - At the top of the main page, the "Advanced" button disappears when scaling by 160%;	
	Severity - major;
	Priority - middle; 
	Description - When zoom in by 160% or more, the "Advanced" button disappears;
	Environment - Browser Mozilla Firefox for Ubuntu v96.0 (64-bit);
	Steps to reproduce - 1. Go to https://www.ebay.com/ 2. Look at the top panel to the right of the 'Search' button 3. Zoom page in to 160%;	
	Actual result - The "Advanced" button disappears when scaling by 160% and more;
	Expected result - A slider should appear that you need to swipe right horizontally to see the button; 
	Assignee - Developer 1;	
	Attachment - https://i.imgur.com/SSwEAr9.png  https://i.imgur.com/mnrN6xV.png 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT
 	git pull
