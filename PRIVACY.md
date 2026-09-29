# FluentClipper privacy policy

Last updated: September 29, 2026

FluentClipper is a clipboard manager for Windows made by Dmitry Novikov. It does not collect, send,
share or sell any personal data. There are no accounts, no ads, no analytics and no telemetry.

## What stays on your computer

- Your clipboard history, templates and settings are stored only on your computer, in
  `%APPDATA%\FluentClipper` and `HKEY_CURRENT_USER\Software\FluentClipper` (the portable version keeps
  them in the `Data` folder next to the program). Nothing is uploaded anywhere.
- Content that password managers mark as secret is not recorded. You can also list programs whose
  content is never recorded.
- If the program crashes, the report (a CRASH line in `log.txt` and a `crash-….dmp` file) stays in the
  same folder and is never sent.

## Network

- The Microsoft Store version makes no network connections of its own. It is updated through the
  Microsoft Store.
- The version from GitHub asks GitHub for the number of the latest version once a day and sends nothing
  else. This can be turned off in Settings → About.
- Web links open in your browser only when you click "Open in browser".
- The editor for formatted text runs on Microsoft Edge WebView2, only while it is open, and loads
  nothing from the internet: web pictures in copied text are not shown, scripts are not run.

## Keyboard

Abbreviations are off by default. When you turn them on, the program watches the keys you press so it
can recognize an abbreviation. It keeps only the last few keys in memory and never writes them to disk
or sends them anywhere. A pasted template does not stay in the clipboard or in the Windows clipboard
history.

## Sync

If you choose a sync folder, your templates and starred clips are written there as files, and your
cloud service (OneDrive, Google Drive, Dropbox and so on) moves them between your computers under its
own privacy policy. The program itself only reads and writes files in that folder. The files are not
encrypted.

## Deleting your data

Settings → Storage clears the history. Uninstalling the Microsoft Store version leaves your data in
`%APPDATA%\FluentClipper`, so the version from GitHub can keep using it; delete that folder to remove
everything. The installer from GitHub asks whether to delete it.

## Contact

Questions and issues: https://github.com/DmitryN71/FluentClipper/issues

---

# Конфиденциальность FluentClipper

Обновлено 29 сентября 2026 года

FluentClipper — менеджер буфера обмена для Windows, автор — Дмитрий Новиков. Программа не собирает,
не отправляет, не передаёт и не продаёт никаких личных данных. Нет учётных записей, рекламы, аналитики
и телеметрии.

## Что остаётся на компьютере

- История буфера, шаблоны и настройки хранятся только на вашем компьютере: в `%APPDATA%\FluentClipper`
  и в `HKEY_CURRENT_USER\Software\FluentClipper` (у портативной версии — в папке `Data` рядом
  с программой). Никуда не загружаются.
- То, что менеджеры паролей помечают как секретное, не записывается. Можно перечислить программы,
  из которых ничего не записывать.
- Если программа упадёт, отчёт (строка CRASH в `log.txt` и файл `crash-….dmp`) остаётся в той же папке
  и никуда не отправляется.

## Сеть

- Версия из Microsoft Store сама в сеть не обращается. Её обновляет Microsoft Store.
- Версия с GitHub раз в день спрашивает у GitHub номер последней версии и больше ничего не отправляет.
  Выключается в настройках: «О программе» → «Проверять обновления».
- Ссылки открываются в браузере только по кнопке «Открыть в браузере».
- Редактор записей с оформлением работает на движке Microsoft Edge WebView2, только пока он открыт,
  и ничего не загружает из интернета: картинки со ссылками на сайты не показываются, скрипты
  не выполняются.

## Клавиатура

Сокращения по умолчанию выключены. Когда они включены, программа смотрит на нажатые клавиши, чтобы
узнать сокращение. В памяти она держит только несколько последних и никуда их не записывает
и не отправляет. Вставленный шаблон не остаётся ни в буфере, ни в журнале буфера Windows.

## Синхронизация

Если выбрать папку синхронизации, шаблоны и записи со звездой записываются в неё файлами, а между
компьютерами их переносит ваше облако (OneDrive, Яндекс Диск, Google Диск, Dropbox и другие) по своим
правилам конфиденциальности. Сама программа только читает и пишет файлы в этой папке. Файлы
не зашифрованы.

## Как удалить данные

Историю очищает раздел настроек «Хранение». После удаления версии из Microsoft Store данные остаются
в `%APPDATA%\FluentClipper`, чтобы ими могла пользоваться версия с GitHub; чтобы стереть всё, удалите
эту папку. Установщик с GitHub при удалении спрашивает, стирать ли её.

## Связь

Вопросы и ошибки: https://github.com/DmitryN71/FluentClipper/issues
