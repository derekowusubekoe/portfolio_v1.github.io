### 1. #wrapper is wrapping everything
Since wrapper is wrapping everything, whatever you want to maximize the wrapper's space, you can set the width to 100%.
e.g Just like I did for the #nav-bar
```css
#nav-bar {
	height: 70px;
	/* start */
	width: 100%;
	/* end */
	// highlight end
	background-color: #1394f0;
	text-align: center;
	margin-bottom: -20px;
}
```

###2. Media Queries for wrapper
you already created a media query which is
```css
@media screen and (max-width: 956px) {
	#wrapper {
		width: 800%;
	}
}
```
What this means is that at 956px and lower, the width of the wrapper should be 800% of the whole page. That's too much.
For responsitivity, make it 100% like;
```css
@media screen and (max-width: 956px) {
	#wrapper {
		width: 100%;
	}
}
```
This way, on views of 956px and above, the width of the wrapper is lower than the entire screen (960px as you set it), but on views smaller than 956px, the wrapper occupies the whole screen, and the nav-bar occupies the whole wrapper.

I already adjusted the style.css, at the media query area