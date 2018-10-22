---
layout: post
title:  "NLP Project"
date:   2018-10-05 00:00:06
categories: projects
---

Additional information to be posted here
Some of the main functions used and their descriptions


{% highlight python %}
def gen(degree, nsims, size, x, out)
        outpoly=[]
        for i in range(nsims)
            indexes=np.sort(np.random.choice(x.shape[0], size=size, replace=False))
            pc=np.polyfit(x[indexes], out[indexes], degree)
            p=np.poly1d(pc)
            outpoly.append(p)
        return outpoly
{% endhighlight %}


Nice way to add links and references!
Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
