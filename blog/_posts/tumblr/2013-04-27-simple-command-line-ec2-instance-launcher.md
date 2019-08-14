---
layout: post
title: simple command line ec2 instance launcher
date: '2013-04-27T21:22:08-04:00'
tags:
- ec2
- python
- aws
- pyec2launcher
- ec2launcher
- boto
tumblr_url: https://b.sricola.com/post/49065267314/simple-command-line-ec2-instance-launcher
---
I have decided to make available publically, a tool that I have written and used over the years. Its simple, to the point, launch instances in AWS EC2, with a python script. Launching an instance is as simple as

> pyec2launcher.py –name test01 –size m1.small –domain test.sri –security\_group testing –launch\_key test\_key

or, run it with no options to get an interactive experience.

Fork the repo and grab the code - [https://github.com/sricola/pyec2launcher](https://github.com/sricola/pyec2launcher)

