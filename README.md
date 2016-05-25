# notes
学习笔记

## jQuery

### UI型插件

#### draggable
拖拽插件$(selector).draggable({options})
  - options-containment:parent 可在父元素内拖动
  - options-target:x|y 可沿着x轴或者y轴移动
  
#### droppable
放置插件$(selector).droppable({options})
  - selector为被放置的区域
  - options 为函数 drop:function(){},当被拖动的元素完全进入该区域的时候触发该函数
  
#### sortable
拖拽排序插件 $(selector).sortable({options}),将序列元素（option或li）按任意位置进行拖拽从而形成一个新的元素序列，实现排序拖拽功能
  - options-delay:2防止与点击事件相冲突，延迟两秒
  - options-opacity:0.35设置被拖动元素的透明度
  
#### accordion
手风琴效果，$(selector).accordion({options}),selector为包含所有需要折叠的容器

#### tabs
选项卡插件selector为包含选项卡和选项内容的容器（将ul中的li定义为标签，再用li中a的href对应id设置标签内容），options可以通过ajax方法动态的获取内容

