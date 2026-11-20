# MySQL Database Backup Assignment

**Student Name:** Thon Yien Thon

## Project Overview

This project demonstrates how to create MySQL database backups using the mysqldump utility in Windows Command Prompt (CMD).

The assignment covers two main tasks:
1. Creating a complete backup of the sales database.
2. Creating a backup of all databases on the MySQL server.

## Requirements

- MySQL Server installed on Windows.
- MySQL Command Prompt or Windows CMD.
- MySQL root username and password.
- mysqldump utility.

## Question 1: Creating a Complete Database Backup

Command:

mysqldump -u root -p sales > sales_backup.sql

Explanation:

- mysqldump is a MySQL utility used to create database backups.
- -u root specifies the MySQL username.
- -p prompts for the MySQL password.
- sales specifies the database to back up.
- > redirects the backup output into a file.
- sales_backup.sql is the backup file name.

## Question 2: Backing Up All Databases

Command:

mysqldump -u root -p --all-databases > all_databases_backup.sql

Explanation:

- mysqldump is used to export database information.
- -u root specifies the MySQL username.
- -p prompts for the MySQL password.
- --all-databases exports all databases on the MySQL server that the account can access.
- > redirects the output into a file.
- all_databases_backup.sql is the backup file name.

## How to Execute the Commands

1. Press Windows + R.
2. Type cmd and press Enter.
3. Navigate to the MySQL bin directory.
4. Execute the backup commands.
5. Enter your MySQL root password when prompted.
6. Check your Desktop for the generated backup files.

## Importance of Database Backups

Regular database backups protect information from accidental deletion, hardware failure, cyberattacks, and system errors. They also make it easier to restore lost information and maintain business operations.

## Importance of Backups Before Server Migration

Backing up all databases before migrating to another server helps prevent data loss. It ensures that important information is safely stored and can be restored on the new server if problems occur during migration.

## Conclusion

Through this assignment, I have learned how to create a backup of a single database and all databases using the mysqldump utility. I have also understood the importance of regular database backups in protecting information and ensuring successful server migration.

**Prepared by: Thon Yien Thon**
