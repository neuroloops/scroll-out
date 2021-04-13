# Scroll-out playground

## Documentation 
[https://scroll-out.github.io/guide.html#what-is-scrollout](https://scroll-out.github.io/guide.html#what-is-scrollout)

## Description

Simple page to use it.

require `data-scroll` atribute to activate on element. 
Effect on 2nd `<h1>` element and 3rd `<section>`


Css attribute needed for transition

```css
[data-scroll] {
  transition: all 2s;
}

[data-scroll='in'] {
  opacity: 1;
  transform: translateX(0);
}

[data-scroll='out'] {
  opacity: 0;
  transform: translateX(-200px);
}
```
