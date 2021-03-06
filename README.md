# de.blitz.infiniteImageScrollableview
Alloy Infinite  Scrollableview Widget

## Overview
The widget shows an infinite *Scrollableview* containing images, the Scrollableview
always has three views to avoid a large number of views.
The Scrollableview loads the next/previews image after swipe gesture ends.


## Features
* Lazy loading
* Limited number of views hold in scrollableview
* No flickering, blinking or flashing either on iOS nor on android 


### How to

* Add the widget to your *Scrollableview:

```xml
<Alloy>
	<Window class="container">
		<ScrollableView id="pics">
			<Widget src="de.blitz.infiniteImageScrollableview" id="ifScollableview"></Widget>
		</ScrollableView>
	</Window>
</Alloy>
```

##Init the Widget

```javascript
$.ifScollableview.init({
            parent      : $.pics,
            index       : 4,
            imageData   : images,
            imageStyle  : $.createStyle({});
});
```


## Styling 

If you need to  style the image while runtime pass a style parameter -> "imageStyle"

```javascript
$.ifScollableview.init({
            parent      : $.pics,
            index       : 4,
            imageData   : images,
            imageStyle  : $.createStyle({});
});
```

Android:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/jtbZjshYN7c/0.jpg)](http://youtu.be/jtbZjshYN7c)

iOS:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/NdyYS4C2-5o/0.jpg)](http://youtu.be/NdyYS4C2-5o)



## Testing
There is a test app in [example](https://github.com/MichelBahl/de.blitz.infiniteImageScrollableview/tree/example) branch.
