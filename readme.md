# 火柴时钟

> 一款有意思的时钟玩具，使用 CSS 渲染过渡动效，引入 base64 格式 data url 图片。

## 引用

* 请保证el是个足够宽的容器，否则元素会折行。
* 你可以通过改变 scale 数值对时钟进行缩放。

```html
<link rel="stylesheet" type="text/css" href="./index.css">
<div id="match"></div>
<script type="text/javascript" src="./index.js"></script>
<script type="text/javascript">
    var mc = new MatchClock({
        el: 'match',
        scale: 0.5
    })
    mc.start()
</script>
```

