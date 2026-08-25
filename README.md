# Porfolio
My portfolio (Jujulien45) here I create and host a web page on github for my portfolio.

Every line of code has been writen by myself so that I learn while creating my porfolio.

## links

- [web page](https://jujulien45.github.io/Porfolio/)

## design guidlines

I still have a lot to learn in design and I don't really know how to make things visualy apealing so I decided to make an IA generate those general guidlines for making a clean and pretty web page.

- Type scale: ... / ... / ... / ...
- Fonts: display = ..., body = ...
- Neutral colors: bg ..., text ..., border ...
- Accent color: ...
- Signature element: ...


And I filled it in myself (I switched to rem, vw and vh units, better for phones scaling).

- Type scale: caption:  0.5rem / body: 0.8rem / subhead: 1.2rem / title: 3rem
- Fonts:                display: consolas or JetBrains Mono, body: IBM Plex Sans
- Neutral colors:       bg: black stars or #1F1F29, text: #e6d7bf, border: #31313b
- Accent color:         #7d1ee9
- Signature element:    ...

## How to launch the project localy ?

Firstly you need Ruby installed on your machine
Then install bundler and jekyll with:
´gem install bundler jekyll´

Then go to the root of the project and run
´bundle init´
then
´bundle add jekyll´

When that's done you can just run this to host localy the web page and see live changes.
´bundle exec jekyll serve´