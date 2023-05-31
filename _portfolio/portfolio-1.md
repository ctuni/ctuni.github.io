---
title: "ChatGPT meal scheduler"
excerpt: "Very simple implementation of a python script with chatGPT to receive meal suggestions directly in your email."
collection: portfolio
---

With the objective of trying to automate thinking of healthy meals each day myself, I once asked ChatGPT-3 to give me a weekly meal plan. It had to be healthy, with a reasonable budget, and not contain food items to which I am allergic. It gave me a very correct plan with breakfast, lunch, and dinner. But of course that output would end up getting lost in the chat-log and be forever forgotten.

That is why I asked the AI to give me a couple more plans, and put them all on a CSV file. Then, I created a Python script to parse that file and output a combination of a breakfast, a lunch and a dinner. With that, and with the help of the `smtplib` library, I added the functionality to have that daily menu sent by email, so I could have a daily email with a whole day's menu suggestion.

In my particular case, this script is running on the crontab of a Raspberry Pi, which means that each night at 22h I get an email from myself to myself, with ideas on what to eat the next day. Here you can see what those mails look like in my inbox ("Avui toca de menjar..." means "Today we're eating..." in Catalan.)

<img src="/images/meal_mail.png"  width="100%">

This was done purely for fun, to practice implementations that went beyond a simple script, since this included obtaining a Google app password for my own account, storing it securely, and using the crontab; all of those things are tools I know of but don't have the opportunity to use on a day to day basis.

You can find this scheduler [here](https://github.com/ctuni/py_meal_scheduler), with instructions on how to use it.

The next natural step wold be to directly implement chatGPT into this, so it's not just a list of suggestions on a csv file. So far, I have signed up for ChatGPT plug-ins, but the beta is not open yet.