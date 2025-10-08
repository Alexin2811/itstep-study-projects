📘 Project Overview

EN:
This repository contains completed practical tasks #3 and #4 from the Clouds 5.0.0 course.
Each task demonstrates work with core AWS services such as IAM, CloudShell, and EC2 (Linux & Windows instances).
All steps were performed using AWS Management Console and AWS CLI.

RU:
В этом репозитории представлены выполненные практические задания №3 и №4 из курса Clouds 5.0.0.
Каждое задание демонстрирует работу с основными сервисами AWS: IAM, CloudShell и EC2 (инстансы Linux и Windows).
Все шаги выполнялись через AWS Management Console и AWS CLI.

🧠 What I learned

EN:

How to use AWS CLI to list IAM users and groups.

How to navigate and manage files inside AWS CloudShell.

How to create and configure Amazon EC2 Linux and Windows instances.

How to use User Data scripts for automatic web server setup.

How to connect to EC2 instances via RDP and verify folder structure.

How to clean up resources after completion.

RU:

Как использовать AWS CLI для получения списка пользователей и групп IAM.

Как управлять файлами и папками в AWS CloudShell.

Как создавать и настраивать Amazon EC2 инстансы Linux и Windows.

Как использовать User Data скрипты для автоматического запуска веб-сервера.

Как подключаться к EC2 через RDP и проверять файловую структуру.

Как корректно удалять ресурсы после завершения работы.

🧩 Task 1 (AWS CLI – Users & Groups)

EN:
Goal:
Learn to use AWS CLI to display information about IAM users and groups.

Actions performed:

Opened AWS CLI via CloudShell.

Executed:

aws iam list-users
aws iam list-groups


Verified output showing existing users and groups.

Result:

RU:
Цель:
Научиться использовать AWS CLI для отображения информации о пользователях и группах IAM.

Выполненные действия:

Открыл AWS CLI через CloudShell.

Выполнил команды:

aws iam list-users
aws iam list-groups


Проверил вывод с отображением существующих пользователей и групп.

Результат:


🧩 Task 2 (CloudShell File Structure)

EN:
Goal:
Create and verify a folder and file structure inside AWS CloudShell.

Actions performed:

Opened AWS CloudShell via AWS Management Console.

Executed commands sequentially:

mkdir testFolder
mkdir testFolder/testSubFolder1
mkdir testFolder/testSubFolder2
echo "Hello from test.txt" > test.txt
echo "Hello from test1.txt" > test1.txt
echo "Hello from test3.txt" > testFolder/test3.txt


Verified with:

ls -R
cat testFolder/test3.txt




RU:
Цель:
Создать и проверить структуру папок и файлов в AWS CloudShell.

Выполненные действия:

Открыл AWS CloudShell через AWS Management Console.

Последовательно выполнил команды:

mkdir testFolder
mkdir testFolder/testSubFolder1
mkdir testFolder/testSubFolder2
echo "Hello from test.txt" > test.txt
echo "Hello from test1.txt" > test1.txt
echo "Hello from test3.txt" > testFolder/test3.txt


Проверил структуру с помощью команд:

ls -R
cat testFolder/test3.txt




🧩 Task 3 (EC2 – Amazon Linux Instance)

EN:
Goal:
Create an Amazon Linux EC2 instance and configure a web server via User Data script.

Actions performed:

Launched Amazon Linux instance in EC2.

Added a User Data script (from EC2Script.txt) to start a web server automatically.

Accessed the public IP address in a browser to verify that the server was running.




RU:
Цель:
Создать Amazon Linux EC2 инстанс и настроить веб-сервер через User Data скрипт.

Выполненные действия:

Запустил Amazon Linux инстанс в EC2.

Добавил User Data скрипт (из EC2Script.txt), чтобы веб-сервер запускался автоматически.

Проверил работу сервера, открыв публичный IP-адрес в браузере.



🧩 Task 4 (EC2 – Windows Instance)

EN:
Goal:
Deploy a Windows EC2 instance, connect via RDP, and manage file structure.

Actions performed:

Created a Windows EC2 instance.

Connected via Remote Desktop Protocol (RDP).

Created folders: first, second.

Inside second created test.txt with content test data.



RU:
Цель:
Развернуть Windows EC2 инстанс, подключиться через RDP и настроить файловую структуру.

Выполненные действия:

Создал Windows EC2 инстанс.

Подключился через Remote Desktop Protocol (RDP).

Создал папки: first, second.

В папке second создал файл test.txt с содержимым test data.

