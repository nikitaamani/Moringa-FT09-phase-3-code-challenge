# Phase 3 -WK3 - Code Challenge: Articles - with database

By Nikita Amani
Date:13TH DEC 2024

## Description

In this code challenge, you will be working with a Magazine domain.

We have three models: `Author`, `Article`, and `Magazine`.

For our purposes, an `Author` has many `Article`s, a `Magazine` has many
`Article`s, and `Article`s belong to both `Author` and `Magazine`.

`Author` - `Magazine` is a many to many relationship.

## Installation Requirements
Git

## Installation instruction

## Project Setup
- clone the repo  
```bash
git clone  git@github.com:nikitaamani/Moringa-FT09-phase-3-code-challenge.git
 from the terminal. 
```
- navigation
```bash 
cd -(change directory) Change directory in your terminal and access it.
```
- open directory on vs-code
```bash 
use ' code .' in your terminal it will lead to you to the vs-code.
```

## Set Instructions

To get started, while inside of this directory.
  - run `pipenv install` 
  - run `pipenv shell` to jump into the shell. 
  - run `python3 app.py` to create the database

The folder structure is as follows:

On the root folder, we have created the main file and named app.py. make use of it to test your code. You re expected to add more code to test your own implementation.

Still on the root path, we have the following folders:

database: Here the most important files are the setup.y where you are expected to write your queries to crate the database. in the same folder, there is another file called connection.py where we have provided the connection string for your database
models: Here we have created 3 files Article.py, Author.py and Magazine.py where you are expected to implement your CRUD methods to interact with the database
tests: Here we have provided few tests to guide you with you own tests
You can add code to the /app.py file to define variables and create sample instances of your objects.

Writing error-free code is more important than completing all of the deliverables listed - prioritize writing methods that work over writing more methods that don't work. You should test your code in the console as you write.

Similarly, messy code that works is better than clean code that doesn't. First, prioritize getting things working. Then, if there is time at the end, refactor your code to adhere to best practices. When you encounter duplicated logic, extract it into a shared helper method.

Technologies used
Github Python
Visual Studio Code

Support and contact details
github.com/nikitaamani


