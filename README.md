# hexo-katex

Use KaTeX to display math in Hexo sites.

## Install 

Install `hexo-renderer-pandoc` and modify /node_modules/hexo-renderer-pandoc/index.js:

```
//var args = [ '-f', 'markdown', '-t', 'html', '--mathjax', '--smart'];
var args = [ '-f', 'markdown', '-t', 'html', '--katex', '--smart'];
```

Then install hexo-katex.

```
npm install hexo-katex --save
```

KaTeX css link will be automatically injected into post, if you want to add it manually, modify `_config.yml`

```
katex:
  css: false
```


## Writing

Inline math `$E = m * c^2$`

Display math

```
$$
E = m * c^2
$$
```
