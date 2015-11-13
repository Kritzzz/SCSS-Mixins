## SCSS mixins


### About


If you use SCSS on a regular basis, you'll know that mixins are a great thing. So are frameworks like Compass, Bourbon and so on. But sometimes these frameworks are just alot more than you actually need for your project.

These are a couple of SCSS Mixins I use quite often. I will be updating and tweaking the list with more projects to come. 

### Changelog

##### [v1.0.0] - 2015-11-13
###### Additions
- Completely restructured the way media queries are compiled. The new 'respond-to' mixin uses a sass-map, which should ideally live in a variables.scss file or config/framework of some sorts.
- Added retina mixin

###### Fixes & Changes
- Removed all vendor-prefixes as this should be done by Autoprefixer and not a sass-mixin
- Removed mixins for 
	- border
	- box-shadow
	- transitions
	- transforms
	- linear gradients (this might come back soon)
- Added tests for the compiled CSS
- Rewrote the README.md

##### [v0.1.0] - 2013-12-29

- Not really sure how I could publish this in the first place.
- v0.1.0 was bad code and I should feel bad.
- Sorry.

### License

The code is free to use under the terms of the MIT license.
