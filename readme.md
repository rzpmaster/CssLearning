# css 

## emmet 语法
- 生成标签
```
div*10      //批量生成
ul>li*4     //父子关系
div*2+p*2   //兄弟关系
div.nav     //带类
div#div     //带id
div.demo$*5 //带参数
div.demo-${content$}*5   //带内容
```

## 显示模式
### 块元素
- 独占一行
- 可以指定高度 宽度，宽度默认是容器的100%
- 可以指定 padding margin
- 可以作为一个容器，内部可以放行内元素或块元素
注意：
- 文字类的元素内不能放块元素（p/h里不能有div）
### 行内元素
- 一行可以有多个
- 不能直接设置高度 宽度，宽度默认是内容的宽度
- 行内元素只能放行内元素
注意：
- a里面不能有再a
- a比较特殊，a里面可以放块元素，但是a转换成块模式更好
### 行内块元素
img input td
- 一行可以有多个，但是有缝隙
- 可以指定高度 宽度，宽度默认是内容的宽度
- 可以指定 padding margin