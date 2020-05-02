# **Collector Documentation**

A program for running experiments on the web Copyright 2012-2015 Mikey Garcia & Nate Kornell

Kitten-release (2019-2020) Anthony Haffey

The developmental (i.e. most up to date) version of this documentation can be found at: [https://docs.google.com/document/d/1SKYIJF1dAjMDS6EHUIwfZm2KQVOzx17S6LbU_oSGxdE/edit?usp=sharing](https://docs.google.com/document/d/1SKYIJF1dAjMDS6EHUIwfZm2KQVOzx17S6LbU_oSGxdE/edit?usp=sharing) 


[TOC]



## 
**Quick start**

To use without installation go to either:



*   [https://ocollector.org](https://ocollector.org) (allows you to choose which release of Kitten you want)
*   [https://some-open-solutions.github.io/collector](https://some-open-solutions.github.io/collector) (will automatically take you to the most recent version of kitten that is stable)

To use without installing, you will need to register with Dropbox and Collector



#### Dropbox registration

Once 


#### Collector registration

Instructions here

Installing Collector on your machine

Why install it?

By using collector

FAQ

How do I get started?

If you have python 3, you can download this as a repository, and then open Collector.py with python to run it.

The first time you run Collector it will need some default information to run smoothly.

Can I use Collector if I am not a programmer?

YES! This program was designed to allow researchers to work with a format they're very familiar with (spreadsheets) to create interactive experiments. As you will see in the tutorial videos, Collector is almost a completely programming free solution. Of course there are times when being able to code will make your life easier but we have tried to minimize user coding wherever possible.

What language is Collector written in?

Collector is written mostly in javascript/Jquery. Formatting of the presentations is controlled mostly by HTML5 and CSS2.

Do I need to ask anyone if I want to use Collector?

No. Collector is distributed under the GNU GPLv3 license (full text can be found in the `/Documentation/` folder). You are free to use, modify, and distribute this program as you wish. If you distribute a modified version of this program you are required to make your modified version available to the public under the same GNU GPLv3 license of the original program. If you are publishing papers that have used Collector experiments we ask that you acknowledge its use somewhere. This isn't a requirement of using this software but we'd like to get the word out to as many people as possible about it's availability.

Collector will be citeable in a prepublication journal imminently.

If you build trial types that you think others would find useful please go to [https://www.collectalk.com](https://www.collectalk.com/) to share.

Included Trial Types

Instruct

Allows you to give participants instructions during the experiment. Instruct trials are special because they do not have to correspond to a line in the stimuli file. To call an instruct trial you insert `Item` (0), `Trial Type` (Instruct), and `Procedure Notes` (instructions and/or HTML code). If you are using instructions that are in your stimuli file you insert the stimuli row as `Item` and in the stimuli file you place your instructions in the `Cue` column. See the Order file used in Condition 1 for an example.

Troubleshooting

My changes aren't being reflected in the experiment. Why?



1. 
Save all your files before running the experiment. 90% of the time when you are having this problem it is because you forgot to save the changes you've made. Seems silly but I run into this all the time.


2. 
Clear your cache. There are extensions for chrome ([http://goo.gl/r961j](http://goo.gl/r961j)) and firefox ([http://goo.gl/r3Zky](http://goo.gl/r3Zky)) that make this process very quick


3. 
Are you sure you're editing the right experiment/folder? (this is for if you edit the experiment files directly, not within the Collector.py interface)
Collaborators

Mikey Garcia

Collector was initially created by Mikey Garcia.

Tyson Kerr