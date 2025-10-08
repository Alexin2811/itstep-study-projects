
⚙️ Power Automate – Conference Registration Flow
📘 Project Overview

This project demonstrates how to automate the process of registering conference participants using Microsoft Power Automate, Microsoft Forms, and Microsoft Teams.

The automation collects registration data from a Microsoft Form and automatically posts it to a dedicated Microsoft Teams channel when a new form response is submitted.

🇷🇺 Русская версия

Этот проект демонстрирует, как автоматизировать процесс регистрации участников конференции с помощью Microsoft Power Automate, Microsoft Forms и Microsoft Teams.

Автоматизация собирает данные из формы Microsoft Forms и автоматически публикует их в специальном канале Microsoft Teams при отправке новой регистрации.

🧠 What I Learned

How to create and connect Microsoft Forms with Power Automate.

How to build an automated workflow triggered by form submissions.

How to configure message posting in Microsoft Teams channels.

How to test and validate automation logic for real-world use.

🇷🇺 Русская версия

Как создать и связать Microsoft Forms с Power Automate.

Как построить автоматический поток, который запускается при отправке формы.

Как настроить публикацию сообщений в канале Microsoft Teams.

Как протестировать и проверить корректность работы автоматизации.

🧩 Task 1 — Creating a Registration Form

Goal:
Design a Microsoft Form to collect participant data for the conference.

Actions performed:

Opened Microsoft Forms.

Created a new form titled Conference Registration.

Added fields:

Name and Surname

City

Profession

Saved the form and confirmed it’s accessible via share link.



🇷🇺 Русская версия

Цель:
Создать форму Microsoft Forms для сбора данных участников конференции.

Выполненные действия:

Открыл Microsoft Forms.

Создал новую форму с названием Conference Registration.

Добавил поля:

Имя и фамилия

Город

Профессия

Сохранил форму и проверил доступность по ссылке.

Скриншоты: form_creation.png, form_fields.png

🧩 Task 2 — Setting Up Microsoft Teams Channel

Goal:
Prepare a dedicated space in Microsoft Teams to display registration notifications.

Actions performed:

Opened Microsoft Teams.

Created a new Team named Conference 2025.

Added a channel called Registrations.

Set appropriate permissions for members.

Screenshots: teams_channel.png, teams_settings.png

🇷🇺 Русская версия

Цель:
Подготовить отдельный канал в Microsoft Teams для отображения уведомлений о регистрации.

Выполненные действия:

Открыл Microsoft Teams.

Создал новую команду с названием Conference 2025.

Добавил канал под названием Registrations.

Настроил права доступа для участников.

Скриншоты: teams_channel.png, teams_settings.png

🧩 Task 3 — Automating the Flow in Power Automate

Goal:
Automate the workflow to post registration details to Teams when a new response is submitted.

Actions performed:

Opened Power Automate.

Created a new Automated Cloud Flow.

Selected the trigger: When a new response is submitted (Microsoft Forms).

Added action: Get response details.

Added action: Post a message in a chat or channel (Microsoft Teams).

Configured dynamic content: Name, City, Profession.

Tested the flow successfully.



🇷🇺 Русская версия

Цель:
Автоматизировать процесс публикации данных о регистрации в Teams при отправке новой формы.

Выполненные действия:

Открыл Power Automate.

Создал новый автоматический облачный поток.

Выбрал триггер: When a new response is submitted (Microsoft Forms).

Добавил действие: Get response details.

Добавил действие: Post a message in a chat or channel (Microsoft Teams).

Настроил подстановку динамического контента: Имя, Город, Профессия.

Протестировал поток — всё работает успешно.

