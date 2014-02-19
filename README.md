###宽屏大图切换效果的插件，主要用作首页大图banner上面的切换
* jQuery Slider plugin
     *
     * 图片滚动插件
     *
     * 参数：
     * 参数1  slider: 容器Slider 如$('.slider')
     * 参数2  dots: 是否出现状态显示点 如$('.dots')
     * 参数3  next: 定义下一张按钮 如$('.btn-right')
     * 参数4  pre: 定义上一张按钮 如$('.btn-left')
     * 参数5  showtime: 定义停留时间 {int} 800
     * 参数6  timer: 5000    // 播放速度 {int} 默认5000

###使用方法：
```
$(document).omSlider({
    slider: $('.slider'),
    dots: $('.dots'),
    next:$('.btn-right'),
    pre:$('.btn-left'),
    timer: 5000,
    showtime: 1000
  });
```