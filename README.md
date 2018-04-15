<<<<<<< HEAD
# Welcome to FinanceMNL's Repository

## Why is this site on GitHub?

We open-sourced the website so everyone can view our source code in which the website is built.

We're also using GitHub for version control.

## I saw this website is powered by Hugo. What is Hugo?

[Hugo](https://github.com/gohugoio/hugo) is a static HTML and CSS website generator written in Go. It is optimized for speed, ease of use, and configurability. Hugo takes a directory with content and templates and renders them into a full HTML website.

Hugo relies on Markdown files with front matter for metadata, and you can run Hugo from any directory. This works well for shared hosts and other systems where you don’t have a privileged account.

Hugo renders a typical website of moderate size in a fraction of a second. A good rule of thumb is that each piece of content renders in around 1 millisecond.

Hugo is designed to work well for any kind of website including blogs, tumbles, and docs.

## How did you build it?

We used [Victor Hugo](https://github.com/netlify/victor-hugo), a Hugo boilerplate for creating truly epic websites.

We use it for building our Hugo website + asset pipelining.

We upload our source code to this repository. Let [Netlify](https://www.netlify.com/github-pages-vs-netlify/) build our production environment which includes asset optimizations and [pre-rendering](https://prerender.io/).

Redirect our domain name provider to Netlify's DNS server (for speed and reliability). Done! 😄
