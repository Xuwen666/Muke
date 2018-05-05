#### cdn
bootcdn 百度cdn
#### 自运行
```javascript
;function(){
	alert(11)
}();
//匿名函数前面加上分号是为了防止前面没有加上分号的
//这样的写法与我们直接写alert(1)有什么区别,更加的严谨
//我们定义了一个匿名的function然后自调用,等于说在定义的同时将这个函数触发了
//再有一个好处就是你把它包到一个function里面,
//他这个域现在是一个本地的域

//比如说我们现在定义一个变量
var a=1;
//那这个a呢默认是在window下的,他会对这个域有污染的可能性
console.log(window.a)
//输出1,如果我们把变量直接定义到外头,等于说在给window定义一个属性
//那如果window他本身有一些其他的属性的呢

//这样做的好处就是不用污染全局变量
```
#### sbulime操作
```html
 div.item{it $}*6可以快捷生成6个div并且里面的值每个都++
    <div class="item">it 1</div>
    <div class="item">it 2</div>
    <div class="item">it 3</div>
    <div class="item">it 4</div>
    <div class="item">it 5</div>
    <div class="item">it 6</div>
```
#### css reset
css样式重置
```css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
```
#### css normalize
保留样式
