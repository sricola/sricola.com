---
layout: post
title: my month in bash history
date: '2012-04-20T01:14:00-04:00'
tags: []
tumblr_url: https://b.sricola.com/post/21428195306/my-month-in-bash-history
---
Inspired by bitly’s own Jehiah ([Jehiah - 2011 Personal Report](http://bit.ly/yH1Dcm)) , I set out to make some sort of personal report myself.

At the&nbsp;beginning&nbsp;of february, I decided to lengthen the history contained in my bash\_history. Doing this is simple enough, edit your

` ~/.bash_profile `

or if you are on a linux machine

`~/.bashrc `

to set

`HIST_SIZE=<insert large number!>`

Once that was done, I went about my month, doing my thing. A couple of days ago, i decided to compile this data into something meaningful. Something visual.&nbsp;

I parsed my bash history by running …

`cat ~/.bash_history | awk '{print $1}' |  sort | uniq -c`

which I fed into a graphing utility to produce …

[![month in bash history](http://f.cl.ly/items/0e112x1I1F0o162o062M/Screen%20Shot%202012-03-12%20at%2012.27.03%20AM.png)](http://sricola.com/bash_history.html)

(click the image to get a more interactive version of the chart)

