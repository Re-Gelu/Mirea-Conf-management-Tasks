# <div align='center'>:poop: Домашние задания </div>

```diff
- Я читаю этот текст и клянусь мамой, что если мне помог этот репозиторий, то я поставлю ему звездочку!
```
## <a name="task1"></a> 1. Эмулятор консоли

Эмулятор командной строки на языке Python с использованием библиотек zipfile (для работы с zip-архивом), sys (получение адреса архива из командой строки), os.path (работа с адресами), calendar (форматирование даты файла для вывода)

Для тестирования необходимо разместить `main.py`, `archive.py` в одном каталоге (для удобства тестируемый архив можно разместить в этом же каталоге, тогда вторым аргументом при запуске main.py передать только имя архива и тип) и запустить `main.py`

Эмулятор поддерживает команды `cd`, `ls`, `ls -l`, `cat`, `pwd`

**Структура программы:**
- `main.py` — содержит функцию `main`, которая создает объект класса `Archive` и в бесконечном цикле передает ему аргументы командной строки, обрабатывая их и вызывая соответствующие методы объекта

- `archive.py` — содержит описание класса `Archive` и несколько вспомогательных функций для работы

**Демонстрация:**

![Image](https://user-images.githubusercontent.com/75813517/191124387-0df4e24c-146e-40dd-a701-84c385c206e7.jpg)
