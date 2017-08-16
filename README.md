hellolorem.com
============

[checkout the site](hellolorem.com)

### Preview
![Post Page](https://github.com/halfsail/halfsail.github.io/tree/master/assets/images/preview.png "Desktop screenshot")

### Build your own version
1. Install [Jekyll](http://jekyllrb.com/)
2. Fork or download this theme
3. Edit the `_config.yml` file (if you make any additional changes to this file, you will need to stop and restart your command in the next step)
4. From your command line, switch to your site directory and build using `jekyll serve`
5. Site will be accessible by viewing http://localhost:4000/

### Contribute To the site
1. Create a GitHub account
2. Click the fork button
3. Click the "Create new file" or " Upload files" on your fork
4. Click "New pull request"
5. Wait for my reply

### Moderate the Comment section
1. Create a [disque](https://disqus.com/) account
2. send me your disque username
3. profit

### Writing A Post
This site uses kramdown for pages. You can check a quick [reference guide](https://kramdown.gettalong.org/quickref.html "Kramdown guide")
To create a post you must include create a new markdown file using this naming scheme **[year]-[month]-[day]-title.md**

Before you start writing your post you have to create a Jekyll head matter. To tell Jekyll key information about the page. This block of code goes at the very top of your markdown file. Here is an example.

~~~ markdown
---
layout: post
title: insert witty title
author: your name
featured_image: assests/images/[file name]
category: design
---
~~~

#### Adding comments
If you want your page to have a comment section all you have to do is add this to the head matter.

~~~ markdown
comments: true
~~~

#### Save a draft
If you want to save an article on the repo. But do not want Jekyll to publish it. You can add this the head matter of the document and Jekyll will ignore it.
~~~ markdown
publish: false
~~~

#### Extra Notes On author and categories
You can not have more than one author and category. See the current categories by looking at the category folder.
Adding more than one will prevent the article from appearing in the category section.

### Create A new page
Creating a new page is the same as creating a post. But instead of creating a markdown file in the `_posts` directory just put it anywhere in the `root` directory. There is no naming requirement. New pages also need some head matter too.
~~~ markdown
---
layout: page
title: [page title here]
featured_image: assests/images/[file name]
permalink: /[page title here]
---
~~~
