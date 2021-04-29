# DarkMode HN

Simple NGINX reverse proxy that injects CSS to dark mode [HackerNews](https://news.ycombinator.com).

Dark mode CSS thanks to: https://userstyles.org/styles/97106/hacker-news-zenburn-dark

## Why do I get an error when trying to login/search/comment?

I very rarely actually comment and since this proxy is publicly available I've decided to save myself some possible grief and disable any HTTP verbs except GET. You can still fill out the login forms and hit submit but NGINX will deny the request. 