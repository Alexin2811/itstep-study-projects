# ☁️ AWS IAM Practical Assignment  
# ☁️ Практическое задание AWS IAM

---

## 📘 Project Overview
This project focuses on mastering **Identity and Access Management (IAM)** within the **AWS Management Console**.  
Through four practical tasks, I created users, groups, and policies, and configured MFA for the root account.  
All operations were performed via the web interface — no CLI or SDK was used.

## 📘 Обзор проекта  
Этот проект направлен на освоение работы с **Identity and Access Management (IAM)** в **AWS Management Console**.  
В ходе четырёх практических заданий были созданы пользователи, группы, политики и настроена MFA для root-аккаунта.  
Все действия выполнялись через веб-интерфейс без использования CLI или SDK.

---

## 🧠 What I learned
- Creating IAM users and groups with different permission levels.  
- Managing AWS access via policies like `AdministratorAccess` and `IAMReadOnlyAccess`.  
- Understanding how group-based access control simplifies management.  
- Enabling **Multi-Factor Authentication (MFA)** for enhanced account security.  

## 🧠 Чему я научился  
- Создавать пользователей и группы IAM с разными уровнями доступа.  
- Управлять доступом в AWS через политики `AdministratorAccess` и `IAMReadOnlyAccess`.  
- Понимать, как групповое управление правами упрощает администрирование.  
- Включать **многофакторную аутентификацию (MFA)** для повышения безопасности аккаунта.

---

## 🧩 Task 1 — Creating the First IAM User
**Goal:** Get familiar with the IAM user — the basic element of AWS access control.  

**Actions performed:**
1. Logged into AWS Management Console using the root account.  
2. Opened **IAM → Users → Add users**.  
3. Entered username `student1`.  
4. Selected **Password — AWS Management Console access**.  
5. Enabled **Require password reset**.  
6. Completed user creation without adding policies or groups.  
7. Logged in under `student1` using an incognito browser.  



### 🧩 Задание 1 — Создание первого пользователя IAM  
**Цель:** Ознакомиться с пользователем IAM — базовым элементом системы доступа AWS.  

**Выполненные действия:**  
1. Вошёл в AWS Management Console под root-аккаунтом.  
2. Открыл **IAM → Users → Add users**.  
3. Ввел имя пользователя `student1`.  
4. Выбрал **Password — AWS Management Console access**.  
5. Включил **Require password reset**.  
6. Завершил создание пользователя без добавления политик или групп.  
7. Выполнил вход под `student1` в режиме инкогнито.  



---

## 🧩 Task 2 — Creating a Group and Assigning a Policy
**Goal:** Learn how to manage access via groups and policies.  

**Actions performed:**
1. Logged in under the root account.  
2. Opened **IAM → User groups → Create group**.  
3. Named the group `ReadOnlyGroup`.  
4. Attached policy `IAMReadOnlyAccess`.  
5. Completed group creation.  
6. Added `student1` to `ReadOnlyGroup`.  
7. Verified access — user can view IAM but not modify resources.  



### 🧩 Задание 2 — Создание группы и назначение политики  
**Цель:** Научиться управлять доступом через группы и политики.  

**Выполненные действия:**  
1. Вошёл под root-аккаунтом.  
2. Открыл **IAM → User groups → Create group**.  
3. Назвал группу `ReadOnlyGroup`.  
4. Добавил политику `IAMReadOnlyAccess`.  
5. Завершил создание группы.  
6. Добавил пользователя `student1` в `ReadOnlyGroup`.  
7. Проверил доступ — пользователь может просматривать IAM, но не изменять ресурсы.  



---

## 🧩 Task 3 — Managing Users and Groups
**Goal:** Create multiple users and organize them with different access levels.  

**Actions performed:**
1. Signed in under the root account.  
2. Created users: `admin1`, `user1`, `user2`, `user3`.  
3. Created groups:  
   - `Admins` with `AdministratorAccess`  
   - `ReadOnlyUsers` with `IAMReadOnlyAccess`  
4. Added `admin1` → `Admins`.  
5. Added `user1`, `user2`, `user3` → `ReadOnlyUsers`.  
6. Verified that users appear in their assigned groups.  



### 🧩 Задание 3 — Управление пользователями и группами  
**Цель:** Создать несколько пользователей и распределить их по группам с разными правами доступа.  

**Выполненные действия:**  
1. Вошёл под root-аккаунтом.  
2. Создал пользователей: `admin1`, `user1`, `user2`, `user3`.  
3. Создал группы:  
   - `Admins` с политикой `AdministratorAccess`  
   - `ReadOnlyUsers` с политикой `IAMReadOnlyAccess`  
4. Добавил `admin1` в группу `Admins`.  
5. Добавил `user1`, `user2`, `user3` в группу `ReadOnlyUsers`.  
6. Проверил отображение пользователей в группах.  



---

## 🧩 Task 4 — Configuring MFA for the Root Account
**Goal:** Add an extra security layer via Multi-Factor Authentication.  

**Actions performed:**
1. Logged in under root account.  
2. Opened **Security credentials** from top menu.  
3. Selected **Assign MFA device**.  
4. Chose **Authenticator app**.  
5. Scanned QR code in **Google Authenticator**.  
6. Entered two consecutive codes.  
7. Confirmed activation — MFA enabled.  



### 🧩 Задание 4 — Настройка MFA для root-аккаунта  
**Цель:** Добавить дополнительный уровень защиты с помощью многофакторной аутентификации.  

**Выполненные действия:**  
1. Вошёл под root-аккаунтом.  
2. Открыл **Security credentials** в верхнем меню.  
3. Выбрал **Assign MFA device**.  
4. Указал **Authenticator app**.  
5. Отсканировал QR-код в **Google Authenticator**.  
6. Ввел два последовательных кода.  
7. Подтвердил активацию — MFA включена.  



---


