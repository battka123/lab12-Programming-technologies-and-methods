# Homework

Сначала установлю Vim: `sudo apt install vim`

Перешёл в тутор `vimtutor ru`

- Перемещение на `hjkl` ;

- Для выхода без сохранения `Esc`(Normal mod) `:a!`;

- Удаляет символ — `x`;

- Вставка — `i` ;

- Добавление — `A` ;

- Для выхода с сохранением — `:wq` ; 

- Для запуска файла `Vim <имя файла>` ;

- Удалить слово `dw` ;

- Удалить строку `d$` ;

Краткий список объектов:

```

    w - от курсора до конца слова, включая последующий пробел.

    e - от курсора до конца слова, НЕ включая последующий пробел.

    $ - от курсора до конца строки.

    ^ - от курсора до начала строки.

```

- Перемещение на 2 словa '2w' вперёд и 0 для перемещения в начало строки;

- Удаление 3 слов `d3w` ; 

- Удаление строки или 2 строк и тд: `dd` или '2dd' ;

- Отмена (Аналог ctr+z) 'u'  ;

- Отмена строки `U`;

- Откат отмены `ctr-R`

- Вставка буфера `p` Аналог (ctr+x ctr+v, только теперь dd p);

- Замена символа 'r' ;

- Режим замены `R` ;

- Команда изменения `ce` ;

- `ctrl-g` месторасположение в файле и информацию о файле;

- Перемещение в самый конец `ctr+G` ;

- Перемещение на номер страницы `<номер страницы>`+`ctr+G` ; 

- Поиск слова `/<слово>` , листать вперёд `n`, листать назад `N`, поиск слова назад `?<слово>`;

- Вернуться назад `ctrl-O`, вернуться вперёд `ctrl-I` ;

- Перемещение курсора на парную скобку `%` ;

- Поиск и замена слова `:s<слово_для_замены>/<заменяемое_слово>` 

```
:#,#s/было/стало/g  где #,# -- номера этих строк.

:%s/было/стало/g    для замены всех вхождений во всем файле.

:%s/было/стало/gc   для поиска всех вхождений во всем файле и запроса подтверждения замены.
```

- `:!` — внешняя команда ;

- `:!ls` выводит файлы в текущем каталоге ;

- `:w <имя_файла>` сохраняет файл ;

- `:!rm <имя_файла>` удаляет файл ;

- Сохранить какой-то кусок отдельно `v`(визуальный режим) + перемещает курсор + `:2 <имя_файла>` ; 

- Вывести с файла `:r <имя файла>` ;

- Создать пустую строку под строкой `o` надо строкой `O`;

-  `e` перемещает курсор по словам ;

- (Аналог ctr+c ctr+v) `v` + выделяем + `y` + выбираем место вставки + `p`;

```
`:set ic` игнорирует при поиске или замене;
`is' отображение частичных совпадений при поиске;
`hls' подсветка всех совпадений при поиске;
Для возвращения учёта регистра при поиске после `set` написать `no`;
```
- `:help` для справки
