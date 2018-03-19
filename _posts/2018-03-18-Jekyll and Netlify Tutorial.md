---
layout: post
title: Jekyll and Netlify Tutorial
---

This tutorial assumes you have a GitHub account and are familiar with Git and the command line.

You'll need to download Jekyll if you haven't already.

You can deploy directly to Netlify. 

Edit the settings in the config.yml file.

Add some blog posts.

git add .
git commit -m "first commit"
git push origin master

![Geometric pattern with fading gradient](/img/sample_feature_img_2.png)

Highlighting for code in Jekyll is done using Pygments or Rouge. This theme makes use of Pygments by default.

{% highlight js %}
// count to ten
for (var i = 1; i <= 10; i++) {
    console.log(i);
}

// count to twenty
var j = 0;
while (j < 20) {
    j++;
    console.log(j);
}
{% endhighlight %}

Type Theme uses KaTeX to display maths. Equations such as $$S_n = a \times \frac{1-r^n}{1-r}$$ can be displayed inline.

Alternatively, they can be shown on a new line:

$$ f(x) = \int \frac{2x^2+4x+6}{x-2} $$
