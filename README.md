这是用于打印部分页面的库，通过计算所要打印的元素样式，生成新的页面。而不仅仅将原页面的所有style搬运过来。
```javascript
//example
import Print from "web-print";
new Print({
    el:"#printMe",
    title:"小白白"
})
```