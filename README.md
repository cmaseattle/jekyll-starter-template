jekyll-starter-template
=======================

Bare bones Jekyll template and install instructions. 

**Assumes you have git and rubygems working properly.*

1. Open terminal
2. Update Ruby Gems: `sudo gem update --system` - *requires system password*
3. Install Jekyll: `sudo gem install jekyll` - *takes a little bit*
4. Make sure Jekyll is running properly: `jekyll -v` - *currently version 1.4.2*
5. Navigate to your working directory: `cd Documents/my/working/directory`
6. Clone this repository: `git clone https://github.com/cmaseattle/jekyll-starter-template.git` and navigate into the directory `cd jekyll-starter-template`
7. Run `jekyll server --watch` - *builds your source and watches for file changes*
8. Your site should be running freely at **localhost:4000**

##Config Includes

* [Pygments](http://pygments.org/) for syntax highlighting - and [syntax.css](https://github.com/mojombo/tpw/blob/master/css/syntax.css) from [Mojombo](https://github.com/mojombo)

Use:

```
{% highlight javascript linenos %}
var waka = Infinity,
    flaka = waka;

function whoDat(flaka) {
    // do that wakaflaka
} 
{% endhighlight %}
```