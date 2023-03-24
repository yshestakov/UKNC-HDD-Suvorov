# IDE HDD controller for UKNC (en)

Original site with photos, schema, drivers and some description:
   http://uknc.narod.ru/Suvorov/index.htm

## Requirements
To boot the system (RT-11) you need to have floppy controller connected and a floppy disk with bootable OS installed.

Sometimes later an image of "HDD" had been provided. Look at `contrib/sys1002.dsk` file in the repo.

## RT-11 drivers

There are 2 files in contrib folder developed by [*form*](https://zx-pk.ru/members/4895-form.html) user of zx-pk forum.

* `wd.mac.txt` -- sources of the `wd.sys` driver
* `wd57.rar` -- prebuilt WD drivers for RT-11

## zx-pk forum thread

https://zx-pk.ru/threads/12218-vinchester-uknts.html?p=295855&viewfull=1#post295855


# Контроллер IDE для УКНЦ (ru)

Печатная плата расчитана на установку в корпус контроллера дисковода.
С большой долей вероятности, на фото один из мастер-контроллеров - на нем создавался и отрабатывался "серийный образец".

Инструкция (и софт) по созданию загрузочного винчестера для УКНЦ (~0.04 Мб)
    http://uknc.narod.ru/Suvorov/uknc_ide.rar

## требования

*Наличие дисковода - обязательно.* Думаю как создать без него ...

