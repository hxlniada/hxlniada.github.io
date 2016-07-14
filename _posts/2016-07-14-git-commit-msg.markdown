---
layout: post
title:  "git代码提交规范"
date:   2016-07-13 10:18:00
categories: git 规范
---
git代码的提交信息中，应该写什么，原文[http://karma-runner.github.io/0.10/dev/git-commit-msg.html](http://karma-runner.github.io/0.10/dev/git-commit-msg.html)

##### Format of the commit message:
>

{% highlight html %}
<type>(<scope>): <subject>

<body>

<footer>
{% endhighlight %}

##### Message subject (first line)
First line cannot be longer than 70 characters, second line is always blank and other lines should be wrapped at 80 characters.


**Allowed `<type>` values:**

* _feat_ (new feature)
* _fix_ (bug fix)
* _docs_ (changes to documentation)
* _style_ (formatting, missing semi colons, etc; no code change)
* _refactor_ (refactoring production code)
* _test_ (adding missing tests, refactoring tests; no production code change)
* _chore_ (updating grunt tasks etc; no production code change)

**Example `<scope>` values:**

* init
* runner
* watcher
* config
* web-server
* proxy
* etc.

The `<scope>` can be empty (eg. if the change is a global or difficult to assign to a single component), in which case the parentheses are omitted.

