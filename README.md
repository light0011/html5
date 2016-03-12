# html5
响应式布局前端页面


知识点总结

1、标签语义化，例如<header></header>，虽然用<div></div>也可以达到同样效果，但这样看起来更易读。

2、搜索区布局中采用相对/决定定位完成效果，并且保证搜索框居中，显示绝对于父元素top、left各50%，但是margin本身的50%距离，从而利用css达到居中效果。可联想hfjs中利用js达到居中效果。

3、当我们故意缩小分辨率时，小于 1280 时，底部会出现滚动条。当我们拉动滚动条时，
发现右侧出现的大量空白。这时由于之前采用了 100%自适应导致的，那我们强行设置这里
虽然是 100%。但如果小于 1280 分辨率，就必须固定在 1280 即可。

