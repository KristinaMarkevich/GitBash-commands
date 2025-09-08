# GitBash-commands

Learning how to use GitBash

1. Сделать папку dir_1 2. Зайти в папку dir_1  3. Создать папку inner_dir_1  4. Посмотреть где ты находишься
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop
$ mkdir dir_1

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop
$ cd dir_1

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ mkdir inner_dir_1

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ pwd
/c/Users/Kristina/desktop/dir_1
```

5. Находясь в папке dir_1 создать пустой текстовый файл tf_1.txt

```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ touch tf_1.txt
```
 6. Находясь в папке dir_1 через команду cat создать текстовый файл tf_2.txt со следующими строками:
- the first 1
- the second 2
- the third 3
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ cat > tf_2.txt
- the first 1
- the second 2
- the third 3
```

 7. Зайти в папку inner_dir_1
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ cd inner_dir_1
```
 8. Через cat сделать текстовый файл tf_3.txt  c любыми строками
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat > tf_3.txt
bug is a flaw, error, or mistake in a software program that causes it to behave  incorrectly.
```

 9. Через cat добавить в текстовый файл tf_3.txt строку “the second 2”
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat >> tf_3.txt

the second 2
```
 10. Через cat добавить в текстовый файл tf_3.txt строку “the sec 2”
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat >> tf_3.txt

the sec 2
```

 11. Через cat добавить в текстовый файл tf_2.txt строку “the sec 3”
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat >> ~/desktop/dir_1/tf_2.txt
the sec 3
```

 12. Через cat добавить в текстовый файл tf_3.txt строку “the SeCoNd 2”
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat >> tf_3.txt

the SeCoNd 2
```

 13. Через cat добавить в текстовый файл tf_2.txt строку “the seConD 2”
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat >> ~/desktop/dir_1/tf_2.txt

the seConD 2
```

 14. Сделать текстовый файл tf_4.txt в котором будет 15 строк.
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat > tf_4.txt
Champion, champion
I'm calling you from the future
To let you know we've made a mistake
And there's a fog from the past that's giving me, giving me such a headache
And I'm back with a madness
I'm a champion of the people who don't believe in champions
I got nothing but dreams inside
I got nothing but dreams
I'm just young enough to still believe, still believe
But young enough not to know what to believe in
Young enough not to know what to believe in, yeah
If I can live through this
If I can live through this
If I can live through this
I can do anything
```

 15. Сделать текстовый файл tF_5.txt в котором будет 13 строк.
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cat > tF_5.txt
All the leaves are brown (all the leaves are brown)
And the sky is gray (and the sky is gray)
I've been for a walk (I've been for a walk)
On a winter's day (on a winter's day)
I'd be safe and warm (I'd be safe and warm)
If I was in LA (if I was in LA)
California dreamin' (California dreamin')
On such a winter's day
Stopped into a church
I passed along the way
Well, I got down on my knees (got down on my knees)
And I pretend to pray (I pretend to pray)
You know the preacher like the cold (preacher like the cold)
```

 16. Вывести список всех файлов в папке.
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ ls
tF_5.txt  tf_3.txt  tf_4.txt
```

 17. Выйти из папки inner_dir_1
```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1/inner_dir_1
$ cd ..
```

 18. Вывести содержимое файла tf_3.txt в терминал. 

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ cat ~/desktop/dir_1/inner_dir_1/tf_3.txt
bug is a flaw, error, or mistake in a software program that causes it to behave  incorrectly.
the second 2
the sec 2
the SeCoNd 2

 19. Найти путь к файлу tf_4.txt

Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/dir_1
$ find . -name "tf_4.txt"
./inner_dir_1/tf_4.txt

 20. Отчистить файл tf_4.txt от содержимого без удаления самого файла.


 21. Найти путь к файлам у которых есть  “tf” в названии.

 22. Найти путь к файлам у которых есть  “tf” в названии и буквы в любом регистре.

 23. Найти строки в файлах где есть комбинация букв “sec” в текущей папке

 24. Найти строки в файлах где есть комбинация букв “sec” в любом регистре в текущей папке

 25. Найти строки в файлах где есть только комбинация букв “sec” в текущей папке

 26. Найти строки в файлах где есть только комбинация букв “sec” в любом регистре в текущей папке

 27. Найти строки в файлах где есть комбинация букв “second” в текущей папке

 28. Найти строки в файлах где есть комбинация букв “second” в любом регистре в текущей папке

 29. Найти строки в файлах где есть комбинация букв “second” во всех папках ниже уровнем

 30. Найти только путь и название файла в строках которых есть комбинация букв “second” в текущей папке

 31. Найти все строки во всех файлах где нет комбинации “second”

 32. Найти только название и путь к файлам где нет комбинации “second”

 33. Вывести в терминал 4 последних строк любого текстового файла

 34. Вывести в терминал 4 первые строки любого текстового файла.

 35. Команда в одну строку. Создать папку и создать текстовый файл с содержиммым.

 36. Команда в одну строку. Переместить в любую одну папку текстовые файлы у которых в содержимом есть слово “sec”

 37. Команда в одну строку. Скопировать в любую одну папку текстовые файлы у которых в содержимом есть слово “sec”

 38. Команда в одну строку. Найти все строки c “sec” во всех текстовых файлах, скопировать и вставить эти строки в один новый созданный текстовый файл.

 39. Команда в одну строку. Удалить текстовые файлы у которых в содержимом есть слово “sec”

 40. Просто вывести в терминал строку “Good job!!”

