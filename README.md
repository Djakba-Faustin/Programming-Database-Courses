# Instructor's Note

Hello — I'm Djakba Faustin. I'm very grateful for the opportunity to share my knowledge with you in Programming III and Advanced Database, courses I teach at the John Willett Institute in Kongsamba, Cameroon. Over this course we will learn and practice the core web and backend technologies: HTML, CSS, JavaScript, PHP, and SQL. We will use Visual Studio Code as our editor and XAMPP to run PHP and MySQL locally.

My approach is hands-on and practical: each lesson includes demonstrations and lab exercises so you can build working projects, reinforce concepts, and gain confidence. We will cover everything from responsive front-end pages and client-side interactivity to secure server-side scripting and robust relational database design. Emphasis will be placed on clean code, security (prepared statements, input validation), and real-world workflows.

I encourage curiosity, collaboration, and regular practice. Ask questions, try the exercises, and experiment beyond the examples. If the institute name or any detail needs correction, let me know and I'll update this introduction.


# Programming & Database Course — Practical Workbook

Welcome to the Programming & Database course. This repository contains practical demonstrations and exercises designed to teach web development and relational database fundamentals using HTML, CSS, JavaScript, PHP, and SQL. The lab environment and recommended tools are Visual Studio Code (VSCode) and XAMPP for running PHP and MySQL locally.

## Course Overview
This course combines front-end development (HTML, CSS, JavaScript) with back-end and database fundamentals (PHP + MySQL). You will build small, focused projects that illustrate how static pages become interactive and how server-side code interacts with a relational database.

## Learning Objectives
- Create responsive HTML/CSS pages and add interactivity with JavaScript.
- Set up a local PHP development environment using XAMPP.
- Design simple relational schemas and perform CRUD operations with SQL.
- Connect PHP code to MySQL and display/query data securely.
- Practice debugging, version control basics, and deployment-ready structuring.

## Tools & Technologies
- Languages: HTML5, CSS3, JavaScript (ES6+), PHP, SQL (MySQL)
- Editor: Visual Studio Code (extensions: PHP Intelephense, Live Server, Prettier)
- Local server: XAMPP (Apache + MySQL)
- Optional: Git for version control

## Setup (Quick)
1. Install VSCode and XAMPP.
2. Start Apache and MySQL via XAMPP Control Panel.
3. Create a project folder inside XAMPP's htdocs (e.g., C:\xampp\htdocs/course-project).
4. Open the folder in VSCode.
5. Use phpMyAdmin (http://localhost/phpmyadmin) to create a database (e.g., course_db) and import the provided `schema.sql`.
6. Open the project in browser via http://localhost/course-project/index.php

## Practical Demonstrations (Suggested Labs)
1. Static site: Build a responsive homepage with header, footer, and a CSS grid gallery.
2. DOM & JS: Add form validation, dynamic content loading, and a simple client-side router.
3. PHP routing: Create a contact form that posts to a PHP endpoint, validates input, and shows confirmation.
4. Database CRUD: Implement a simple user or notes manager with create/read/update/delete backed by MySQL.
5. Secure queries: Demonstrate prepared statements and discuss SQL injection prevention.

## Best Practices Covered
- Separation of concerns (HTML/CSS/JS/PHP)
- Secure database access (use prepared statements)
- Simple input validation (client + server side)
- Clean, commented code and incremental commits (use Git)

## Where to Go Next
After finishing the labs, explore frameworks like Laravel (PHP) or front-end frameworks (React/Vue) and deployment to a shared host or cloud service.

## Support & Contributions
If you want additional starter files, lesson plans, or fully worked example code (HTML/CSS/JS, PHP scripts, and a ready-to-import schema.sql), open an issue or contact the instructor.

Happy learning — build small, test often, and iterate!
