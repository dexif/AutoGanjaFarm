Автоматизация Фермы GanjaWars
==========

License: GPL v3

[Evgeniy Spitsyn](http://spitsyn.net)

__Внимание!__ Для работы скрипта необходимо чтобы была постоянно открыта страница фермы!

FEAUTURES:
--------------------

На данный момент скрипт умеет автоматически садить, поливать, собирать и вскапывать грядки.

TODO:
----------

В ближайшее время будет добавлена карта посадок, чтобы иметь возможность автомтически садить нужные растения на нужных грядках :)

Зачем я это пишу?
- Как говорится Just For Fun :)

HOW TO:
----------

Установка:

0.  В __FireFox__ необходимо установить дополнение [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

    В __Google Chrome__ дополнение [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

1.  Отредактировать строки раздела `//SETTINGS` в скрипте

    ```JS
        //SETTINGS
        var req=false;  //Хотите ли вы чтобы перед посадкой скрипт спрашивал вас. (true|false)
        var r=false;    //Стандартный выбор если нет запроса садить/не садить (true|false)
        var pageid=1;   //Страница на которой ноходится растение (1-10)
        var plantid=3;  //Номер растения на странице (1-4)
        //SETTINGS
    ```

2.  Установить скрипт

3.  Для работы скрипта необходимо чтобы постоянно была открыта страница фермы
