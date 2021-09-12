# Написать скрипт
## Который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
1. Создать папку			`mkdir foldername`
4. Зайти в папку			`cd foldername`
5. Создать 3 папки			`mkdir foldername1 foldername2 foldername3`
6. Зайти в любую папку			`cd foldername1`
7. Создать 5 файлов `(3 txt, 2 json)	touch 1_text_file.txt 2_text_file.txt 3_text_file.txt 1_json_file.json 2_json_file.json`
8. Создать 3 папки			`mkdir foldername1 foldername2 foldername3`
13. Выйти из папки на уровень выше	`cd ..`
```sh
mkdir myscript
cd myscript
touch myscript.sh
vim myscript.sh
(i)
#!/bin/bash
mkdir myscript_result
cd myscript_result
mkdir foldername
cd foldername
mkdir foldername1 foldername2 foldername3
cd foldername1
touch 1_text_file.txt 2_text_file.txt 3_text_file.txt 1_json_file.json 2_json_file.json
mkdir foldername1 foldername2 foldername3
ls -la
mv -t foldername1 1_json_file.json 1_text_file.txt
(esc) :wq
chmod +x ./myscript.sh
./myscript.sh
```
