---
layout: post
title: Optimal ssh configuration
categories: blog
excerpt: Two advises on how to ssh with ease that will save you a tremendous time.
authorname: Ismail Mechbal
authornickname: The boss
authorcity: Casablanca & Stockholm
authorphone: +212 600 828 689
authoremail: ismail@unik.ma
googleauthor: https://plus.google.com/110158564608845019382
---
Everyday, or let say every hour at the minimum we login to our development servers @[Unik](http://unik.ma/ "Unik"), the usual workflow is to

> 1. ssh dev@dev.unikar.ma
  2. type the password

"Silky Smooth Hopping" is a term coined by Paul Irish at the HTML5DevConf held by marakana on November 5th, 2012.
It’s a way to login via SSH painlessly and with ease.

It is very easy to setup, so let begin

### **I. Saving the password**
1. We will copy the public ssh key we’ve created with github to the local machine’s clipboard using this command
> cat ~/.ssh/id_rsa.pub | pbcopy

2. Paste the content to "authorized_keys" in your remote server (you might need to create it if doesn't exist)
> ~/.ssh/authorized_keys

### **II. Silky Smooth Hopping**
1. Create a new ssh config file in the ~/.ssh
> nano ~/.ssh/config

2. Paste the following

> Host unikar
    HostName dev.unikar.ma
    User dev


###Conclusion

From now on, we'll simply type

> ssh unikar

instead of

>ssh dev@dev.unikar.ma

in the terminal and it'll login automatically without asking you for a password.


Hope this will help you, and if you have any question feel free to write it.
