# CSS-pure--
用CSS画图，学习的小demo

1.learn1是用纯CSS样式画的一个卡通人物-哆啦A梦

2.practice1是用CSS3的transition属性制作的一个嫦娥奔月的小动画

      transition: property duration timing-function delay(property规定设置过渡效果的 CSS 属性的名称。 duration规定完成过渡效果需要多少秒或毫秒。timing-function规定速度效果的速度曲线。delay定义过渡效果何时开始。);
      
          其中transition-timing-function: linear|ease|ease-in|ease-out|ease-in-out|cubic-
          bezier(n,n,n,n);
      
              linear	规定以相同速度开始至结束的过渡效果（等于 cubic-bezier(0,0,1,1)）。
              
              ease	规定慢速开始，然后变快，然后慢速结束的过渡效果（cubic-bezier(0.25,0.1,0.25,1)）。
              
              ease-in	规定以慢速开始的过渡效果（等于 cubic-bezier(0.42,0,1,1)）。
              
              ease-out	规定以慢速结束的过渡效果（等于 cubic-bezier(0,0,0.58,1)）。
              
              ease-in-out	规定以慢速开始和结束的过渡效果（等于 cubic-bezier(0.42,0,0.58,1)）。
              
              cubic-bezier(n,n,n,n)	在 cubic-bezier 函数中定义自己的值。可能的值是 0 至 1 之间的数值。

3.transform是用CSS3的transform属性制作的一个照片展开效果

      transform 属性向元素应用 2D 或 3D 转换。该属性允许我们对元素进行旋转(rotate)、缩放(scale)、移动(translate)或倾斜(skew)。
      
      这里还运用到了css3的transform-origin属性，transform-origin 属性允许设置旋转元素的基点位置。
      
4.animation是用CSS3的animation属性制作的一个页面loading效果

      animation 属性是一个简写属性，语法：animation: name duration timing-function delay iteration-count direction; 用于设置六个动画属性：
      
            animation-name	规定需要绑定到选择器的 keyframe 名称。
            
            animation-duration	规定完成动画所花费的时间，以秒或毫秒计。
            
            animation-timing-function	规定动画的速度曲线。
            
            animation-delay	规定在动画开始之前的延迟。
            
            animation-iteration-count	规定动画应该播放的次数。
            
            animation-direction	规定是否应该轮流反向播放动画。
            
      这里使用了animation-delay使5根线条缩放产生时间差，进而展现载入画面的一种动态效果。
