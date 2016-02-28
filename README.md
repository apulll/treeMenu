# A jQuery Plugin for Tree Menu (树形结构菜单自动生成jQuery插件)
==================================


## 使用文档
使用该jquery插件，需要加载以下三个文件

```
<link type="text/css" rel="stylesheet" href="jqtree.css">
<script src="../js/jquery.min.js"></script>
<script src="plugeTree.js"></script>
```
假设需要在body元素下生成一个树形结构菜单，则需要在body下使用createTree方法，创建树形结构菜单。

> 例如:

```
var jsonData = [
   {"id":"1","pid":"0","name":"江苏"},
   {"id":"2","pid":"0","name":"湖北"},
   {"id":"3","pid":"0","name":"江西"},
   {"id":"4","pid":"0","name":"山东"},
   {"id":"5","pid":"1","name":"苏州"},
   {"id":"6","pid":"1","name":"南京"},
   {"id":"10","pid":"5","name":"常州"},
   {"id":"11","pid":"5","name":"吴江"},
   {"id":"12","pid":"5","name":"张家港"}
];
$('body').createTree(array);
// 执行函数createTree(array)即可生成树形结构菜单。
```
效果如图：

![](http://blog.liuxj.com/img/treeMenu.png)

