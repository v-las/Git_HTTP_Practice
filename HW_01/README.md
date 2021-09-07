# HW #1 Terminal Linux

1) Посмотреть где я			pwd
2) Создать папку			mkdir foldername
3) Зайти в папку			cd foldername
4) Создать 3 папки			mkdir foldername1 foldername2 foldername3
5) Зайти в любую папку			cd foldername1
6) Создать 5 файлов (3 txt, 2 json)	touch 1_text_file.txt 2_text_file.txt 3_text_file.txt 1_json_file.json 2_json_file.json
7) Создать 3 папки			mkdir foldername1 foldername2 foldername3
8. Вывести список содержимого папки	ls -la
9) + Открыть любой txt файл		vim 1_text_file.txt
10) + написать туда что-нибудь.		(i) Insert text
11) + сохранить и выйти.		(esc) :wq
12) Выйти из папки на уровень выше	cd ..
13) переместить любые 2 файла, которые вы создали, в любую другую папку.	mv -t foldername1 1_json_file.json 1_text_file.txt
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.	cp -t foldername2 2_json_file.json 2_text_file.txt
15) Найти файл по имени								find -L /c/Courses/Group_22/ -name "3_text_file.txt"
16) просмотреть содержимое в реальном времени (команда grep)			grep -i insert foldername1/1_text_file.txt
17) вывести несколько первых строк из текстового файла				head foldername1/1_text_file.txt
18) вывести несколько последних строк из текстового файла			tail foldername1/1_text_file.txt
19) просмотреть содержимое длинного файла (команда less)			less -F -E /c/Windows/setupact.log
20) вывести дату и время							dt=$(date '+%d/%m/%Y %H:%M:%S');
										echo "$dt"
										
1) Отправить http запрос на сервер.
	curl -iv \
	-X GET 'http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000'
	
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
