# Section Part
- In General, this is in `<body></body>` tag.

# Main tags
- main  
- article  
- section  
- nav  
- aside  
- h1 ~ h6  
- header  
- footer  
- address  

# Explain

## フローコンテンツ（Content Categories）
- In General, this is in `<body></body>` tag.  
<https://developer.mozilla.org/en-US/docs/Web/HTML/Content_categories>

## `<article>` Tag
- A news, or an article.

## `<nav>` Tag
- It is called as a 'Global Navication'(グローバル属性).


## `<section>` Tag
- `<section>` tag should always have a heading.  
- In General, this tag has a title explained as a heading(見出し) tag `<h1> ~ <h6>` and a content.

## ETC
- It is allowed to use `<header>` or `<footer>` in a multiple time.  
(EX)  
```
<header>
    <nav>
        <li>Home</li>
        <li>About</li>
        <li>Projects</li>                
    </nav>
</header>
<article>
    <header>
        <h3>NovaCat News</h3>
     </header>
    <p>
        NovaCat get passed on HTML5 Professional Level.1!
    </p>
    <footer>
        Admin: NovaCat
    </footer>
  </article>
<footer>
2024 Copyright
</footer>
```

# Reference
<https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section>