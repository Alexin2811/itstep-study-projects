# 🧰 Git_entrance

---

## 📘 Project Overview  
This project documents my first complete journey with Git — from installation and configuration to creating repositories, performing commits, restoring file versions, and publishing to GitHub.  
The goal was to build a solid foundation for version control and to understand the workflow between local and remote repositories.

**Русская версия:**  
Этот проект описывает мой первый полный путь работы с Git — от установки и настройки до создания репозиториев, выполнения коммитов, восстановления версий файлов и публикации на GitHub.  
Цель — создать прочную базу для работы с системой контроля версий и понять процесс взаимодействия между локальными и удалёнными репозиториями.

---

## 🧠 What I learned  
- Installing and configuring Git across operating systems.  
- Initializing and managing local repositories.  
- Tracking changes and committing files.  
- Restoring previous versions using commit hashes.  
- Publishing repositories via GitHub and GitHub Desktop.  
- Understanding `git status`, `git add`, `git commit`, `git log`, and `git restore`.

**Русская версия:**  
- Установка и настройка Git на разных ОС.  
- Инициализация и управление локальными репозиториями.  
- Отслеживание изменений и выполнение коммитов.  
- Восстановление предыдущих версий с помощью хэшей коммитов.  
- Публикация репозиториев через GitHub и GitHub Desktop.  
- Понимание ключевых команд: `git status`, `git add`, `git commit`, `git log`, `git restore`.

---

## 🧩 Task 1 — Installing Git  
**Goal:** Install Git and verify that it runs correctly.  

**Actions performed:**  
1. Downloaded Git for Windows from [git-scm.com](https://git-scm.com/download/win).  
2. Installed using default settings.  
3. Opened the terminal and ran:
   ```bash
   git --version
Confirmed that the version displayed successfully.

Captured screenshots of the result.

Русская версия:
Цель: Установить Git и убедиться, что он работает корректно.

Действия:

Скачал Git для Windows с git-scm.com.

Установил с настройками по умолчанию.

Открыл терминал и выполнил:

bash
Copy code
git --version
Проверил, что версия отображается корректно.

Сделал скриншоты результата.

🧩 Task 2 — Configuring Username and Email
Goal: Set up personal identity for commits.

Actions performed:

Executed:

bash
Copy code
git config --global user.name "Alexin"
git config --global user.email "alex@example.com"
git config --global --list
Confirmed that username and email appear in the configuration list.

Русская версия:
Цель: Настроить имя пользователя и почту для коммитов.

Действия:

Выполнил команды:

bash
Copy code
git config --global user.name "Alexin"
git config --global user.email "alex@example.com"
git config --global --list
Убедился, что имя и почта отображаются в списке настроек.

🧩 Task 3 — Creating a Working Folder
Goal: Create and navigate to a project directory.

Actions performed:

Created a folder:

bash
Copy code
mkdir D:\MyGitTest
cd D:\MyGitTest
Verified the path in the terminal.

Русская версия:
Цель: Создать рабочую папку и перейти в неё.

Действия:

Создал папку:

bash
Copy code
mkdir D:\MyGitTest
cd D:\MyGitTest
Проверил путь в командной строке.

🧩 Task 4 — Initializing the Repository
Goal: Initialize a new Git repository and check hidden files.

Actions performed:

Ran:

bash
Copy code
git init
Verified the hidden .git folder:

bash
Copy code
dir /a
Confirmed repository initialization with a screenshot.

Русская версия:
Цель: Инициализировать новый Git-репозиторий и проверить наличие скрытой папки.

Действия:

Выполнил:

bash
Copy code
git init
Проверил скрытую папку .git:

bash
Copy code
dir /a
Подтвердил инициализацию репозитория скриншотом.

🧩 Task 5 — Adding and Committing Files
Goal: Create and commit files with quotes.

Actions performed:

Created files roosevelt.txt and franklin.txt with quotes.

Checked file status:

bash
Copy code
git status
Added both files to staging area:

bash
Copy code
git add .
Committed:

bash
Copy code
git commit -m "Add roosevelt.txt franklin.txt with initial content"
Русская версия:
Цель: Создать и закоммитить файлы с цитатами.

Действия:

Создал файлы roosevelt.txt и franklin.txt с цитатами.

Проверил статус:

bash
Copy code
git status
Добавил файлы в staging area:

bash
Copy code
git add .
Выполнил коммит:

bash
Copy code
git commit -m "Add roosevelt.txt franklin.txt with initial content"
🧩 Task 6 — Adding More Files
Goal: Add multiple new quote files and commit them.

Actions performed:

Created tolkien.txt, shakespeare.txt, thomas.txt.

Checked untracked files with git status.

Added all files and committed:

bash
Copy code
git add .
git commit -m "Add tolkien.txt, shakespeare.txt, and thomas.txt with quotes"
Русская версия:
Цель: Добавить несколько новых файлов с цитатами и выполнить коммит.

Действия:

Создал tolkien.txt, shakespeare.txt, thomas.txt.

Проверил неотслеживаемые файлы с помощью git status.

Добавил и закоммитил:

bash
Copy code
git add .
git commit -m "Add tolkien.txt, shakespeare.txt, and thomas.txt with quotes"
🧩 Task 7 — Modifying and Logging Changes
Goal: Edit a file and track commit history.

Actions performed:

Added a new quote to franklin.txt.

Checked modified files:

bash
Copy code
git status
Added and committed:

bash
Copy code
git add franklin.txt
git commit -m "Update franklin.txt with new quote"
Viewed commit history:

bash
Copy code
git log
Русская версия:
Цель: Изменить файл и просмотреть историю коммитов.

Действия:

Добавил новую цитату в franklin.txt.

Проверил изменения:

bash
Copy code
git status
Добавил и закоммитил:

bash
Copy code
git add franklin.txt
git commit -m "Update franklin.txt with new quote"
Просмотрел историю коммитов:

bash
Copy code
git log
🧩 Task 8 — GitHub & GitHub Desktop
Goal: Practice remote repository creation and synchronization.

Actions performed:

Registered on GitHub and confirmed email.

Created WebCreatedRepo and uploaded files via browser.

Initialized GitPractice locally, added and committed quotes.

Practiced restoring older versions using git restore --source=<hash>.

Created and published repositories through GitHub Desktop (DesktopRepoTest).

Added and pushed new file doyle.txt.

Verified updates on GitHub.

Русская версия:
Цель: Освоить работу с удалёнными репозиториями и синхронизацию через GitHub Desktop.

Действия:

Зарегистрировался на GitHub и подтвердил почту.

Создал WebCreatedRepo и загрузил файлы через браузер.

Инициализировал локально GitPractice, добавил и закоммитил цитаты.

Отработал восстановление предыдущих версий через git restore --source=<hash>.

Создал и опубликовал репозитории через GitHub Desktop (DesktopRepoTest).

Добавил и запушил файл doyle.txt.

Проверил обновления на GitHub.

