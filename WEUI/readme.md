html中<P>和<h1><h2><h3><h4>的区别就是定义的标签不一样，<p>是段落，而<h>是标题。
　　<p> 标签定义段落。会自动在其前后创建一些空白。浏览器会自动添加这些空间，您也可以在样式表中规定。
　　<h1-h?>标签定义标题。<h1> 定义最大的标题。<h6> 定义最小的标题。
<p>和<h>标签都是段落标签会自动换行
 var oPrimary = document.getElementById('primary');获取标签
    oPrimary.onclick = function(){ 点击事件
           //this.innerHTML='Hello World!'
           this.classList.add('active') ;点击后获取的类
       padding是定义边框距离制定位置大小
       margin是指从自身边框到另一个容器边框之间的距离，就是容器外距离。

padding是指自身边框到自身内部另一个容器边框之间的距离，就是容器内距离。
document.createElement()是在对象中创建一个对象，要与appendChild() 或 insertBefore()方法联合使用。其中，appendChild() 方法在节点的子节点列表末添加新的子节点。insertBefore() 方法在节点的子节点列表任意位置插入新的节点。