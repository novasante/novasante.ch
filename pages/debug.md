---
permalink: /debug/
title: "Debug page"
---

<h1>Site configuration</h1>
```
{{ site | debug }}
{{ site.meta | debug }}
{{ site.meta.title | debug }}
{{ site.github | debug }}
{{ site.defaults | debug }}
```

<h1>Page configuration</h1>
```
{{ page | debug }}
{{ page.defaults | debug }}
{{ page.description | debug }}
```