---
layout: post
title: "Hello World"
date: 2012-09-18 19:43
comments: true
categories: ["hello-world"] 
---

Here goes my First post using [Octopress](http://octopress.com). Its a blogging software for hackers. :)  
Checking code snipets:  

*  Python:  
{% codeblock Python Class lang:python Defining a Class %}
class Python():
	def __init__(self):
		pass
	def __version__(self):
		print '3.3'
{% endcodeblock %}

*  Ruby:  
{% codeblock Ruby code lang:ruby Ruby code on http://ruby-lang.org Ruby Language %}
# Output "I love Ruby"
say = "I love Ruby"
puts say
 
# Output "I *LOVE* RUBY"
say['love'] = "*love*"
puts say.upcase
  
# Output "I *love* Ruby"
# five times
5.times { puts say }
{% endcodeblock %}
