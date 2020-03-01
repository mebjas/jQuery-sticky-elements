jQuery-sticky-elements
======================

jquery plugin to create sticky elements -- worrying how to keep your `div` 
at position you want, want to create rules for it to stay & hide, `jQuery-sticky-elements` is 
made just for you.

[View Demo](https://blog.minhazav.dev/research/jquery-sticky-elements)

**Screenshot**
![Screenshot](https://preview.ibb.co/cCzA07/Capture.png)

=============

How to use
=============
Checkout the [demo page](https://blog.minhazav.dev/research/jquery-sticky-elements) on more details on how to use.

```html
<div id="grid5"> some content here </div>

<script type="text/javascript" src="../js/jquery.js"></script>
<script type="text/javascript" src="../js/jquery.sticky.elements.js"></script>
<script type="text/javascript">
	$("#grid5").stikify({rate: 3.4, cieling: -100});
</script>
```

just include jQuery, our sticky element plugin & you have just `stikified` it!

```js
$("#grid4").stikify({
	floor: 100,		// the height at which the items starts to scroll
	rate: 1.6,		// speed corresponding to scroll
	cieling: -100,	// max height (pixel) that the item can move up.
	trans: true,	// transparency with scroll
});
```

