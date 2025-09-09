---
layout: blogs 
title: Blogs
search_exclude: true
permalink: /blogs/
---
# This is how I set up my chromebook for my Computer Science Principles class with Mr. M 

## 1. Creating accounts

The very first thing one must do is to set up a GitHub account and an account on Open Coding Society. 

## 2. Using VSCode on personal chromebook

I access VSCode through a website provided by the school with the URL:

    kasm.opencodingsociety.com

You must log in with your Open Coding Society user and password

## 3. Repositories

Now that the very basics are down, the next step is to clone the main repositories that you will be working in.

To do this, open a terminal in VSCode by right clicking on the screen of the kasm ubuntu website.

Next, you want to type in the following code to first configure your machine:

    mkdir opencs
    cd opencs
    git clone https://github.com/Open-Coding-Society/student.git
    cd student/
    ./scripts/activate.sh
    ./scripts/venv.sh
    code .

This will clone Open Coding Society's student repository to your machine so that you will have your own version of it to access for the course. 

In that terminal, you will then want to clone the pages repository from Open Coding Society in the same fashion. 