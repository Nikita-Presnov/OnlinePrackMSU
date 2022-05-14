# OnlinePrackMSU

Репрезеторий для онлайн пректикума кафедры фотоники и физики микроволн ФФ МГУ

## Настройка окружения и запуск
### Linux/UNIX
Установите пакеты `python3-dev python3-venv python3-pip`
Затем откройте терминал в папке с этим файлом(`README.md`), как правило это можно сделать с помошью комбинации клавиш `Shift+F4` в файловом менеджере. Введите последовательно следующие команды:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
### Windows
Установите `python >= 3.6` c оффициального сайта, не забудтье указать что `python` нужно добавить в `PATH`. Затем откройте терминал в папке с этим файлом(`README.md`), как правило это можно сделать через меню правой кнопки мыши с зажатым `Shift` в файловом менеджере. Введите последовательно следующие команды:
```shell
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
jupyter notebook
```
