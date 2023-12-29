---
layout: post
title:  "First blog"
date:   2023-12-29
categories: blog
---
I've been trying to create a personal blog for a long time, feeling that I need a long term documentation of my ideas and development, and of course after encoutering many other's well-built blogs.

Finally I spent a day setting this up. If you're also new to web development like me, maybe you can find some inspiration below. You can refer to my [source code](https://github.com/shenyangshi/shenyangshi.github.io) as well. I used:

1. [Github pages](https://pages.github.com/), as a website deployment server and a git server to store the codes. Basically it has all your codes and voluntarily lends you a server for others to visit.
2. [Jekyll](https://jekyllrb.com/). I can never get the spelling right... It's a ruby based static site generator. It basically transfer your plain text in markdown and the structure design in yaml to machine-understandable html codes. There are many templates up to choose, I used [Hadejack](https://hydejack.com/) which allows me using a huge picture as the background. You'll need some ruby knowledege in this step, just remember that gem is similar to package in Python, and Gemfile stores the necessary package, while bundle will handle the package installation like pip.
3. [Cloudflare](https://www.cloudflare-cn.com/). I bought the domain name and the DNS service from it. The domain name Github gives you is hard to remember by yourself or your visitors, but you can buy a new domain name (mine is www.shenyang-shi.com) from a company (domain name broker?, I never understand how DNS service and domain name market cna be like this), and they let visitor know your new domain name goes to the numeric IP address. Github has a [tutorial](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site), while you can even build your website on [Cloudflare servers](https://pages.cloudflare.com/) directly out of Github pages! They have very good migration for this. Remember to catch up with some DNS knowledge when you set up A and CNAME, basically A links domain to IP, and CNAME links domain to domains.
4. Most time you spent will on solving bugs on ruby/gem and digging the Jekyll configs to make the page as you want. But finally you'll find the time is well-spent. Good luck.
