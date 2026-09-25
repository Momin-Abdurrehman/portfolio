# Personal Portfolio - CS313 Web Engineering Lab 3

Momin Abdurrehman | CMS ID 502825 | BS-DS2A

A five-page personal portfolio built with plain HTML and a single external
stylesheet. No JavaScript and no CSS frameworks are used.

## Project structure

```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── my_photo.jpeg
│   ├── squash.jpg
│   ├── mun.jpg
│   ├── coding.jpg
│   └── reading.jpg
└── README.md
```

## Pages

- `index.html` - home page with a short introduction and education table
- `hobbies.html` - squash, MUN, AI side projects, reading
- `skills.html` - technical skills and spoken languages
- `gallery.html` - image gallery (5 images)
- `contact.html` - contact details and a message form

## CSS notes

All styling lives in `css/style.css`, which every page links in its `<head>`.
The layout is arranged with `float` and `clear`:

- the navigation items float left so the links sit in one horizontal row
- the profile photo floats left on the home page so the intro text wraps beside it
- the gallery tiles float left and wrap into rows
- the contact detail cards float into two columns

A `nav::after` clearfix and a few `<div class="clear"></div>` elements stop the
floated blocks from pushing the following sections around.

## Live site

Deployed with GitHub Pages: https://momin-abdurrehman.github.io/portfolio/
