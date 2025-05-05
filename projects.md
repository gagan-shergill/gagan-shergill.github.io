---
layout: inner
title: Projects
permalink: /projects/
---

## Projects

<div class="projects">

### Project One
![Project One Image](assets/images/project1.jpg){: style="max-width: 300px;" }
**Description:** A brief description of Project One, highlighting its goals or impact.  
[View Project](https://example.com/project1)

---

### Project Two
![Project Two Image](assets/images/project2.jpg){: style="max-width: 300px;" }
**Description:** A brief description of Project Two, outlining what it does and its relevance.  
[View Project](https://example.com/project2)

## Markdown

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](/index.html).

/*--------------------------------------------------------------
	1.0 Defaults
--------------------------------------------------------------*/

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}

body {
  background-color: #e9edf0;
  @extend %opensans;
  -webkit-font-smoothing: antialiased;
}
{% endhighlight %}

#### YAML

{% highlight yaml %}
### Phantom settings
paginate: 10
footer_text: '© 2018 Jami Gibbs'
admin_name: 'Jami Gibbs'
google_analytics: "UA-9999999-99" # Update with your own tracking ID

#### Phantom Navigation menu
enable_nav: true
nav_item:
  - { url: '/', text: 'Home' }
  - { url: '/about', text: 'About' }
  - { url: '/projects', text: 'Projects' }
{% endhighlight %}