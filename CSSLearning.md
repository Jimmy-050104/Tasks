# 对CSS的理解
CSS是对HTML文档进行一种渲染
# CSS语法规则
CSS规则由两个主要的部分构成：选择器，以及一条或多条声明  
如：`选择器 {属性：值；属性：值}`
CSS声明总是以分号;结束，总以大括号{}括起来
# CSS选择器 
要在HTML元素中设置CSS样式，需要在元素中设置"id"和"class"选择器
## id选择器
id 选择器可以为标有特定 id 的 HTML 元素指定特定的样式。  
HTML元素以id属性来设置id选择器,CSS 中 id 选择器以 "#" 来定义。  
以下的样式规则应用于元素属性 id="para1":
```
#para1
{
  text-align:center;
  color:red;
}
```
**ID属性不要以数字开头**
## class选择器
class 选择器用于描述一组元素的样式，class 选择器有别于id选择器，class可以在多个元素中使用。    
class 选择器在 HTML 中以 class 属性表示, 在 CSS 中，类选择器以一个点 . 号显示：  
在以下的例子中，所有拥有 center 类的 HTML 元素均为居中。  
`.center{text-align:center;}`
你也可以指定特定的HTML元素使用class  
在以下实例中，所有的p元素使用class="center"让该元素的文本居中  
`p.center{text-align:center;}`  
多个class选择器可以使用空格分开：  
```
.center{text-align:center;}
.color{colot:#ff0000;}
```
**类名的第一个字符不能用数字**



