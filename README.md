# portfolio-website

## Nav Bar

Added both Desktop and mobile responsive such that when it is below 1200px, it is considered mobile.
```css
@media screen and (max-width: 1200px) {
  #desktop-nav {
    display: none;
  }
  #hamburger-nav {
    display: flex;
  }
}
```

## Jump to a specific section of a page 
This actually adds `#contact` to the end of the url which get redirected to the section of the page with `id='contact'`

```html
<button class="btn btn-color-1" onclick="location.href='./#contact'">
            Contact me
          </button>
```

## Download pdf 
This allows browser window to open the document 
```html
   <button
            class="btn btn-color-2"
            onclick="window.open('./assets/resume-example.pdf')"
          >
            Download CV
          </button>
```


## Some ideas
Here are some ideas that I will need to research.
- [ ] Pulling the activities from github to my personal website.
- [ ] Sticky header with nav at the top and image become smaller.
