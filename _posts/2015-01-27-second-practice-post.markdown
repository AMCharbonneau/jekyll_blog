---
layout: post
title: Second Practice Post A bit about me 
---

This is my first paragraph. In the next paragraph I'm going to write about me. I don't think I'll have a third paragraph. 

I am 33 years old. I was born in the Northeast Coast of the USA, but I consider Seattle my home. I'm currently living like a nomad, travelling from place to place, while I learn web development. 

I was wrong, this is my third paragraph. <!-- linenos adds line numbers -->
{% highlight ruby linenos %} 
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}