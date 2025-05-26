---
title: "Field Booker"
summary: "Had to book school fields as the frisbee captain. Unfortunately, said captain was too lazy to stay up until midnight to click through a user-unfriendly website."
description: "An automated solution for booking sports fields using Python and Selenium, designed to save time and reduce frustration."
date: 2023-01-13
tags: ["automation", "Python", "web scraping"]
# repoUrl: "https://github.com/e-mny/field_booker"
draft: false
toc: true
readTime: true
autonumber: true
math: false
showTags: true
---

## Why This Project?

Back in the day, I was in charge of booking fields for frisbee trainings. Since the booking for slots starts at **12am**, someone had to be **READY** to book at that time.

One would have to go through the following steps:

- Log in using your school account
- Navigate through multiple pages
- Select the location to book
- Confirm the booking
- Hope that no one else booked the slot earlier than you

Booking is super competitive. Frustrates me when I couldn't book the field because of external factors like internet speed, a slow computer, or just pure bad luck.

- **The Idea**: To automate the process of booking sports fields and be the first to book.
- **Why It Matters**: ~~To let me sleep~~ To let me focus on studying during that time.

---

## Investing Time to Save Time

I've read about RPA (Robotic Process Automation), and it is used to speed up processes on repetitive tasks. Hence, I used **Python** and **Selenium** to speed up this repetitive task that occurs every week.

With **Selenium**, I can automate and 'click' on inputs of a webpage, allowing me to be away from the computer but still booking the field.

The booking system will send an email upon successful booking &ndash; the smell of victory over other people who tried to book.

- **How To Build**: This project was simply made with **Python**, **Selenium** and scheduled cron jobs.

---

## The Hard Work Paid Off..?

It worked. It allowed me to have supper in peace. It allowed me to go to the toilet in peace. It allowed me to sleep in peace.

<br />

Well... kinda...

Sometimes it broke. Sometimes it wasn't fast enough to get the field.

Maybe others used bots as well &ndash; possibly written in **C++** or **Rust**, resulting in faster execution time.

Regardless, it was a rather fun project, solving a real-world problem with a solution that only required a few days of work. Receiving the email that says "Successful Booking" meant that my bot worked!

- **The Reflection**: **Python** is fast and intuitive when it comes to writing code, but for time-sensitive tasks, the language used matters.

---

## Afternote

Just after I left school, they revamped the website, so my code probably doesn't work anymore LOL.

It was good while it lasted.
