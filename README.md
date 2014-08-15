jQuery-sticky-elements
======================

jquery plugin to create sticky elements -- worrying how to keep your `div` 
at position you want, want to create rules for it to stay & hide, `jQuery-sticky-elements` is 
made just for you.

[View Demo](cistoner.org/sample/jQuery-sticky-elements/)
=============

How to use
=============
```html
<script type="text/javascript" src="../js/jquery.js"></script>
<script type="text/javascript" src="../js/jquery.sticky.elements.js"></script>
<script type="text/javascript">
	$("#grid5").stikify({rate: 3.4, cieling: -100});
</script>
```

just include jQuery, our stiky element plugin & you have just `stikified` it!


```js
$("#grid4").stikify({floor: 100, rate: 1.6, cieling: -100, trans: true, rate: 3.4});
```
means:
 - The grid `id - grid4` will not go below 100px height, above -100px height, will get transparent with scroll. Its `scroll-rate` will be `3.4` **times** normal scroll!
 
#### For any queries mail me to minhazav@gmail.com
