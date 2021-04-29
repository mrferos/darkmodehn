# DarkMode HN

## tl;dr go to https://hn.galindo.io

Simple NGINX reverse proxy that injects CSS to dark mode [HackerNews](https://news.ycombinator.com).

Dark mode CSS thanks to: https://userstyles.org/styles/97106/hacker-news-zenburn-dark

## Why this instead of X, Y, or Z solution?

I saw a post asking for a Dark Mode and I thought that'd be nice since I tend to read HN before bed - when I'd most like a dark mode. I have an iPhone so I didn't know of any solutions off the top of my head for it, so I decided I could probably just whip up a reverse proxy for this right quick. 

After having finished this, I found a neat Shortcut based solution [here](https://beccao.io/posts/custom-css-with-shortcuts) for those who don't want to use this/

## Why do I get an error when trying to login/search/comment?

I very rarely actually comment and since this proxy is publicly available I've decided to save myself some possible grief and disable any HTTP verbs except GET. You can still fill out the login forms and hit submit but NGINX will deny the request. 