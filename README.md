# FreeCodeCamp: Kitty Ipsum Translator

[Русское описание ниже](#описание-проекта-на-русском)

An educational project created as part of the freeCodeCamp "Relational Database" course. This workshop focuses on advanced Linux command-line text processing, data manipulation, and automation using Bash scripting.

### Tech Stack
* **Scripting & Automation:** Bash (Shell Scripting)
* **Linux CLI Utilities:** sed, awk, grep, wc, head, tail, cat
* **Data Streams:** Input/Output redirection (`>`, `>>`, `<`), Pipes (`|`)
* **Text Patterns:** Regular Expressions (Regex)

### Key Achievements & Skills Learned:
* Mastered text file manipulation and data extraction directly from the Linux terminal.
* Used `grep` and regular expressions to search, filter, and count specific patterns within complex text files.
* Utilized `sed` for stream editing to dynamically replace strings and modify text on the fly.
* Combined multiple CLI tools using pipes (`|`) to create efficient data processing pipelines.
* Handled standard input, standard output, and standard error streams, redirecting outputs to logs (`stdout.txt`, `stderr.txt`).
* Developed executable Bash scripts with proper shebang (`#!/bin/bash`) and permission management (`chmod +x`).

### Project Structure
* `script.sh` — the main Bash script that processes, filters, and analyzes the Kitty Ipsum text files.
* `translate.sh` — a specialized script that uses `sed` to replace specific words (e.g., transforming "cat" references into "dog" alternatives).
* `kitty_ipsum_1.txt` / `kitty_ipsum_2.txt` — raw input text files used for processing.
* `stdout.txt` / `stderr.txt` — output and error logs generated during stream redirection tasks.

---

## Описание проекта на русском

Учебный проект, созданный в рамках воркшопа от freeCodeCamp по курсу Relational Database. Этот воркшоп посвящен продвинутой обработке текста в командной строке Linux, манипуляции данными и автоматизации с помощью Bash-скриптов.

### Технологический стек
* **Скрипты и автоматизация:** Bash (Shell Scripting)
* **Утилиты Linux CLI:** sed, awk, grep, wc, head, tail, cat
* **Потоки данных:** Перенаправление ввода/вывода (`>`, `>>`, `<`), конвейеры (Pipes `|`)
* **Шаблоны текста:** Регулярные выражения (Regex)

### Чему я научился в этой части:
* Извлекать, фильтровать и анализировать данные из текстовых файлов напрямую через терминал Linux.
* Использовать утилиту `grep` и регулярные выражения для поиска и подсчета специфических паттернов в текстах.
* Применять потоковый редактор `sed` для динамической замены строк и модификации текста «на лету».
* Связывать несколько CLI-инструментов в одну цепочку с помощью конвейеров (`|`) для эффективной обработки данных.
* Управлять потоками данных, разделяя стандартный вывод и ошибки в отдельные лог-файлы (`stdout.txt`, `stderr.txt`).
* Создавать исполняемые Bash-скрипты, настраивать шебанг (`#!/bin/bash`) и права доступа файлов (`chmod +x`).

### Структура проекта
* `script.sh` — основной Bash-скрипт, который обрабатывает, фильтрует и анализирует файлы Kitty Ipsum.
* `translate.sh` — специализированный скрипт, использующий `sed` для замены определенных слов (например, перевод текста из "кошачьего" в "собачий").
* `kitty_ipsum_1.txt` / `kitty_ipsum_2.txt` — исходные текстовые файлы для обработки.
* `stdout.txt` / `stderr.txt` — файлы логов, созданные в ходе выполнения задач на перенаправление потоков.
