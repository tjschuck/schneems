---
layout: post
title: Explain Shell, from your Shell
date: '2013-09-17T14:30:27-05:00'
tags:
- shell
permalink: /post/61514247453/explain-shell-from-your-shell
---
<p>If you aren&#8217;t massively in love with <a href="http://explainshell.com/">Explain Shell</a> then you&#8217;ve not been on the internet today (or at least following the same people I do on twitter). It&#8217;s an easy way to see what a unix command does from a web interface. The web interface is great, but wouldn&#8217;t it be cool if you could open it from your command line? If someone gave you a command like <code>tar xzvf archive.tar.gz</code> it would be amazing to be able to run:</p>

```sh
$ explain tar xzvf archive.tar.gz
```

<p>And have the results pop up in your browser. Well with a simple <a href="http://github.com/schneems/explain_shell">explain_shell script</a> now you can!</p>

<p>First off you can <a href="https://github.com/schneems/explain_shell#install">install as a ruby gem</a> or as a <a href="https://github.com/schneems/explain_shell#without-rubygems">shell script</a>. Then reload your environment (open a new tab) and explain commands to your hearts content!</p>

```sh
$ explain git log --graph --abbrev-commit --pretty=oneline origin..mybranch
```

<p>It&#8217;s that simple.</p>
