# Arsound Desktop — releases

Downloads of Arsound Desktop (a free SoundCloud client for Windows 10/11 x64, no ads) live here
under **Releases**, on the right. This repository holds no source code; see `NOTICE.md` for the
terms the program and its files are under.

## Install

1. Download `Arsound-<version>-setup.exe` from the latest release and run it. No administrator
   rights are needed: it installs for your user only, adds a Start menu shortcut and an entry in
   Windows "Apps" (where you can remove it).
2. No installer wanted? Take `arsound-desktop-<version>-win64.zip` instead, unpack it anywhere and
   run `arsound.exe`. A copy started from an unpacked zip offers once to install itself, so that
   later updates go over it.
3. Sign-in windows need the Microsoft Edge WebView2 Runtime (already on Windows 11 and most
   Windows 10 machines); the program points at the download page if it is missing.

## Updates

The program checks this repository's releases on its own (the banner, or Settings, "Check for
updates"). When a newer full release is out it offers **Install**: the program downloads the setup
of that release, checks its size and SHA-256, and runs it; the setup closes Arsound, replaces the
files in the same folder and starts it again. Settings, the library, sign-ins and downloaded music
stay where they are (`%APPDATA%\Arsound`, `%LOCALAPPDATA%\Arsound`, `Music\Arsound`). Running a
newer `Arsound-<version>-setup.exe` by hand does the same.

---

# Arsound Desktop — выпуски

Здесь лежат загрузки Arsound Desktop (бесплатный клиент SoundCloud для Windows 10/11 x64, без
рекламы): раздел **Releases** справа. Исходного кода в репозитории нет; условия — в `NOTICE.md`.

## Установка

1. Скачайте `Arsound-<версия>-setup.exe` из последнего выпуска и запустите. Права администратора не
   нужны: установка только для вашего пользователя, ярлык в меню «Пуск» и запись в «Приложениях»
   Windows (оттуда можно удалить).
2. Без установщика: `arsound-desktop-<версия>-win64.zip` — распаковать куда угодно, запустить
   `arsound.exe`. Копия из распакованного zip один раз предложит установить себя, чтобы обновления
   шли поверх неё.
3. Окна входа требуют Microsoft Edge WebView2 Runtime (он есть в Windows 11 и в большинстве
   Windows 10); если его нет, программа покажет страницу загрузки.

## Обновления

Программа сама проверяет выпуски этого репозитория (плашка или Настройки, «Проверить обновления»).
Когда выходит новый полный выпуск, она предлагает **Установить**: скачивает установщик выпуска,
сверяет размер и SHA-256 и запускает его; установщик закрывает Arsound, заменяет файлы в той же
папке и запускает программу снова. Настройки, библиотека, вход и скачанная музыка остаются на месте.
Запуск более нового `Arsound-<версия>-setup.exe` вручную делает то же самое.
