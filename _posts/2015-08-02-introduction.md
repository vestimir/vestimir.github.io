---
layout: post
title: Introducing the blog
---

So this is my new blog.

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

![image caption](https://cdn3.vox-cdn.com/uploads/chorus_asset/file/3913040/eater1_2040.0.jpg)
