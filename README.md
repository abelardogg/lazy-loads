# lazy-loads
lazy loads with jQuery
## Demo
[codepen demo](https://codepen.io/abelardogg/full/JrjyOO/)

### usage

#### JS
```javascript
/** 
* lazyLoad(animationDuration,windowPosition, opacityLevel)
*
* animationDuration: int
* windowPosition: int
* opacityLevel: decimal 
*/

$(document).ready(function(){
		lazyLoad(1000,window.innerHeight, 1);
})

$(document).on('scroll touchmove',function(){
	lazyLoad(1000,window.innerHeight, 1);
});

```

#### HTML

```html
<img class="lazy-img" alt="test" data-awake="false" data-img-src="img.jpg">
```
