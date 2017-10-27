---
layout: post
title:  "Hints for Git"
date:   2017-10-27 02:42:55 +0000
categories: new
---
<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->

Here are some common git commands. I mainly follow the tutorial in [Liao Xuefeng's blog].
There may be some mistakes.

`git init`: convert current folder into a git repository.  
`git add filename1 filename2 .../--all`: add specific file(s) or all files to the 'buffer' of the current git repository.  
`git commit -m "some comments"`: commit the change within the 'buffer' with some comments.  
`git reset commitSHA1`: back to the specific commit state.  
`git rm filename`: reverse to add.  
`git checkout filename`: undo some file delete ops.  
`git remote add origin git@github.com:username/repositoryname.git`: commit the local repo 'origin' to the remote repo.  
`git push origin master`: merge the 'origin' to the master brench.  
`git clone git@github.com:username/repositoryname.git`: copy the whole remote repo to the local repo.  
`git pull --all`: get all the updates from the remote repo.

[Liao Xuefeng's blog]: https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000