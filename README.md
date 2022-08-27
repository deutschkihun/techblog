# techblog.deutschkihun

This repository is a source code for tech blog application by deutschkihun. This project is based on the react and next.js framework.

The blog posts are stored in `/_posts` as Markdown files with front matter support. Adding a new Markdown file in there will create a new blog post.

To create the blog posts we use [`remark`](https://github.com/remarkjs/remark) and [`remark-html`](https://github.com/remarkjs/remark-html) to convert the Markdown files into an HTML string, and then send it down as a prop to the page. The metadata of every post is handled by [`gray-matter`](https://github.com/jonschlinkert/gray-matter) and also sent in props to the page.

## Demo

[https://techblog-deutschkihun.vercel.app/](https://techblog-deutschkihun.vercel.app/)

## Use this project in your local machine

Your blog should be up and running on [http://localhost:3000](http://localhost:3000)! in your local machine. If it doesn't work, post on [GitHub discussions](https://github.com/vercel/next.js/discussions).

# Notes

`this application` uses [Tailwind CSS](https://tailwindcss.com) [(v3.0)](https://tailwindcss.com/blog/tailwindcss-v3).
