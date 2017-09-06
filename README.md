### Q 1. ：图标在div中如何消除边距。让图片完全充满div.
### Q 2: 鼠标移到li上，如何让a改变颜色
    A: 设置a标签转换成块状元素，然后设置a元素的line-height等于父标签的高度即可

### Q 3：清除浮动的几种方法
    A： 方式一：通过 clear：both属性清除
      需要提前定义好 css 参数。然后在dom中添加包含一个class名为clear的标签，如<div class="clear"></div>

      方式二：父元素设置 overfolw:hidden;
      如：<div style="overflow:hidden">
            <div style="float:left"></div>
          </div>
