# blank-layout
This is my small template to quick start in layout creating.


## What technologies using?
HTML5, CSS3 + SASS (scss), Bootstrap 4 (only grid!) jQuery, FontAwesome icons

## What Plugins included?
- [Slick slider v1.6.0](http://kenwheeler.github.io/slick/)
- [fancybox 3.0](http://fancyapps.com/fancybox/3/)

## Have you added anything else?
Not yet.

## How to use slick plugin?
It's very simple:
```html
<div class="your-class">
  <div>your content</div>
  <div>your content</div>
  <div>your content</div>
</div>

<script>
$(document).ready(function(){
  $('.your-class').slick({
    setting-name: setting-value
  });
});
</script>
```

For more documentation please visit official site.

## How to use fancybox plugin?
It's more simple, that using slick slider :)
```html
<a data-fancybox="gallery" href="big_image.jpg"><img src="small_image.jpg"></a>
```

For more documentation please visit official site.

## How to use modal windows?

With this, we will again help fancybox plugin:

You have to place a DIV container into the content of the page:
```html
<a data-fancybox data-src="#hidden-content" href="javascript:;">
  Show modal window
</a>
```

And then simply create a link using `data-src` attribute that matches CSS id selector of the element you want to open (`#hidden-content` in this example):
```html
<div style="display: none;" id="hidden-content">
  <h2>Hello</h2>
  <p>World!</p>
</div>
```

# In this version:
### updates:
- We have abandoned to use own modal-window script in favor of built-in functionality fancybox3;
- Added flex-alignment for bootstrap.

### bugfixes:
- none

# TODO:
- ajax-php sendmail form+script
- smth else..