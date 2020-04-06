---
description: Code widget to embed a combinary stream into any system of framework
---

# Embed Code

### Parameters you can provide for the widget

**Show search bar**  
data-search="1"

**Show filters**  
data-filter="1"

**Items to display by default**  
data-items="40"

**Trim the body text of the components to x characters**  
data-limit-char="500"

### Embed Code

Copy these three lines of code into your html to embed a combinary stream to your website:

```
<div class="combinary" data-url="https://netidee-stream.combinary.com/items.json" data-items="40" data-search="1" data-filter="1" data-limit-char="500"></div>
<link href="https://unpkg.com/@acolono/combinary/widget.css" media="all" rel="stylesheet" type="text/css" />
<script src="https://unpkg.com/@acolono/combinary/widget.min.js" type="text/javascript"></script>
```

Please note, you can update CSS line with your own CSS file, if you like to have own layout.   
As a good starting point - you could use our CSS or SCSS  
[https://www.npmjs.com/package/@acolono/combinary](https://www.npmjs.com/package/@acolono/combinary)

Online Demo:

{% embed url="https://codepen.io/Grienauer/pen/mdJMRoY" %}



