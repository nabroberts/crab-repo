## Basic News Package Template

This template contains the following files:

* [Bootstrap 4.3](https://getbootstrap.com/)
* [Jquery 3.4.0 Slim](https://jquery.com/download/)
* [Local Google Fonts Montserrat and Merriweather](https://google-webfonts-helper.herokuapp.com/fonts)
* [Skrollr 0.6.3 (included but unused)](https://github.com/Prinzhorn/skrollr)

It's a basic template with a large background video at the opening, and a single column of text. Some examples of interpolating images throughout the text is included.

<!-- ![https://github.com/jrue/basic-template/blob/master/assets/screenshot.png](https://github.com/jrue/basic-template/blob/master/assets/screenshot.png) -->

<!-- 
## How to use this template in your project

Simplest way is to use npm (if you have it installed). You can [download it here](https://nodejs.org/en/).

1. Create a folder where you want your project to live, and open the folder window in your Finder.
2. Open the Terminal program on your Mac.
3. Type in `cd ` (make sure to add a space after the "cd")
4. Drag the small folder icon at the top of the window over the Terminal window and press return.
5. Type the following:

```bash
npm install jrue/basic-template
``` 
-->


## Customizations

The following custom CSS classes were added:


#### .full-screen

```html
<div class="full-screen">
```

Sets the width and height of an element to 100 percent of the viewport for a fullscreen effect.

#### .background-video

```html
<video class="background-video" loop muted autoplay playsinline preload>
	<source src="assets/background-video.mp4" type="video/mp4">
</video>
```

Creates a fullscreen background video, positioned absolutely, and adjusted based on the ratio of the viewport (16/9). 


#### .dark-shade

Creates a semi-transparent black background.

```html
<div class="dark-shade">
```

#### .light-shade

Creates a semi-transparent white background.

```html
<div class="light-shade">
```

#### .text-black .text-white

Make the text either black or white.

```html
<p class="text-black">text black</p>
<p class="text-white">text white</p>
```

#### .pull-right or .pull-left

These will make images protrude from the main content well by adding negative margin. A mediq query undoes this effect for mobile (below 576px).

```html
<figure class="pull-right"> ... </figure>
<figure class="pull-left"> ... </figure>
```
