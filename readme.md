# JS 30

start from 7.28

<h2>Day 1 Drum Kit</h2>

学习了keyCode的获取方法，以及通过attribute获得元素的方式：

​		`const key = document.querySelector(.key[data-key="${e.keyCode}"]);`

此处也可配合`querySelectorAll`得到集合。

集合中的元素添加Listerner，需要通过遍历：

```javascript
keys.forEach(key => key.addEventListener("transitionend", removeTransition));
```

其他的技巧：

​	function中可以提早return

