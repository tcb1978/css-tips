# Quick CSS Tips - A Heavily Opinionated Guide

## Use a Font
Serif fonts are rarely the answer, so the default Times New Roman has to go. This is probably the easiest change you can make to get your site looking better instantly.

Pick a sans-serif font that’s easy to read for the majority of your site. You may want to throw some extra style in for things like headings or nav menus, and this is where you have some more leeway  if you want to use a fancier font. Make sure it’s still readable. 

[Google fonts](https://fonts.google.com/) is my go-to. If you have a Creative Cloud subscription, you can also use [TypeKit](https://typekit.com/) to get access to some paid fonts that are included in your subscription. If you don’t have time to browse fonts or can’t settle on one, [Better Helvetica](https://css-tricks.com/snippets/css/better-helvetica/) is a good fallback.

Don’t use too many fonts, 2 is probably the max you’re going to want, maybe 3. You still want everything to look like it matches, and too many fonts will slow your load time.

## Add Some Color
Color goes a long way, so you definitely want to use it. Whether or not that way is the right way depends on how you use it. Don’t use excessively bright colors. Instead of yellow, try goldenrod. Instead of red, try crimson, etc. 
Find a good base color and base your borders, shadows, and accents on a close shade. You can use [Paletton](http://paletton.com) for help if you need to.

## Use Backgrounds
Unless you're going for that clean, minimalistic look, you probably want something other than a plain white background.  The easiest way to do this is to just set a background color.  

Background images can look great, but you have to be careful when selecting one because it can obscure your content. You also have the option to set your content to have a white background so that the image only shows up on the sides.  This doesn't work with all images, but it can be a good option for pictures that still look good from just the sides.  You can also do a semi-transparent background for your content if you really need a hard-to-work with image to show.

A good middle ground between plain color and background image is often a gradient.  As Jemaine says, "If it looks like crap, just throw a gradient on it and no one will know."  He's kind of right.  I prefer using very subtle gradients so that you probably wouldn't notice it if you didn't know it was there, but it still has the same effect.

The last option, if you really want to get crazy, is to use a video as your background.  It's a bit of a pain, you shouldn't use it in more than one place, and it will slow your load time, but can look great if you pull it off right.

**Note:**  &nbsp; iPhones will not display a background image if the size is too big, so scale them to a good middle ground for all devices, or use separate image files for mobile display.  It also a good idea to always specify a background color even when using a background image in case the image can't be loaded.

## Use pictures
You don't need a lot of pictures, but have least a few to make things more interesting.  If you need pictures, get them from somewhere like [Unsplash](https://unsplash.com/) so you know you're using them legally.  You can also use the google search tools to help with this, just make sure you're reading the page because most of these you have to be sure to credit in a certain way:

![Google](https://i.imgur.com/5iS9xaW.png)

If at all possible, use vector images so they can be scaled without impacting resolution. You can also drawn your own in vector form, I use Adobe Illustrator for most of mine.

## Don’t Leave All Your Links Underlined
Sometimes it’s necessary to make it obvious a link exists, but things like nav links and headers often look much better without it.

## Soften Corners
This depends entirely on design. Sometimes you need sharp, crisp, corners. Often though, there’s something to be said for sanding down the edges with a small border-radius. I probably use 3px most often.

## Padding and Containers
I can’t stand when text runs right up against a page/container. You almost always need some kind of padding in your divs. This also applies to page as a whole, so use a container to keep content away from the sides of the screen. You can make them yourself, or use something like [Bootstrap](https://getbootstrap.com/) / [Foundation](https://foundation.zurb.com/) / [Osseous](https://austindelamar.com/osseous/) for predefined, responsive container classes. Don’t forget to pad the top and bottom of your body as well.

## Flex and Grid
You use to need way too many floats or a css framework to grid things out, but there are far better ways now. Escape clear-fix nightmares and breakpoint based classes and use Flexbox or CSS Grid. Both do some amazing things and are fairly easy to learn if you don’t know them already.  These are all great resources:

* [Flexbox Zombies](https://geddski.teachable.com/p/flexbox-zombies) - Flexbox game
* [Flexbog Froggy](http://flexboxfroggy.com/) - Flexbox game
* [CSS Grid Course](http://cssgrid.io/) - Wes Bos's free course
* [CSS Grid Video](https://www.youtube.com/watch?v=jV8B24rSN5o) - Traversy Media video
* [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - CSS Tricks Guide
* [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - CSS Tricks Guide
