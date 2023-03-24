# IDE HDD controller for UKNC (en)

Original site with photos, schema, drivers and some description:
   http://uknc.narod.ru/Suvorov/index.htm

## Requirements
To boot the system (RT-11) you need to have floppy controller connected and a floppy disk with bootable OS installed.

Sometimes later an image of "HDD" had been provided. Look at `contrib/sys1002.dsk` file in the repo.

## Original drivers and utilitis

There is `contrib/uknc_ide.rar` archive with original utilities and drivers developed by Oleg.H

    Archive: uknc_ide.rar
    Details: RAR 4

     Attributes      Size     Date    Time   Name
    ----------- ---------  ---------- -----  ----
        I.A....     24576  2008-10-01 15:48  WDX.DOC
        I.A....      8704  2008-09-28 23:06  WDMAN.LST
        I.A....      3584  2008-10-04 20:21  KDAY.SAV
        I.A....      2560  2008-10-03 22:44  WDBOOT.SAV
        I.A....      1536  2008-10-01 15:51  WDR.SAV
        I.A....     20992  2008-10-01 15:51  WDX.SAV
        I.A....     20992  2008-10-01 15:51  WDXR.SAV
        I.A....      1024  2008-10-01 15:51  WD.SYS
        I.A....       939  2008-10-04 19:58  readme.txt
    ----------- ---------  ---------- -----  ----
                    84907                    9


## RT-11 drivers by Form

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

