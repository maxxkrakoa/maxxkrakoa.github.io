# Playing around with GitHub Pages
Stuff

## Testing
More stuff

### Testing more
Even more stuff


## Posts
{% for post in site.posts %}
    * <a href="{{ post.url }}">{{ post.title }}</a>
    {{ post.excerpt }}
{% endfor %}
  
