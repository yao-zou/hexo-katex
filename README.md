# hexo-katex

Use KaTeX to display math in Hexo sites.

## Install 

Install `hexo-render-pandoc` and modify index.js:

```
//var args = [ '-f', 'markdown', '-t', 'html', '--mathjax', '--smart'];
var args = [ '-f', 'markdown', '-t', 'html', '--katex', '--smart'];
```

Then install hexo-katex.

```
npm install hexo-katex --save
```
