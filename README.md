# TernLight - 基于HTML5 Canvas的图元绘制框架
TernLight是基于HTML CANVAS API的Javascript库，提供在HTML页面上绘制图元——如流程图的能力（类似Viso）。目前在chrome、firefox、IE9上测试通过。
借助于TernLight，开发人员可以定制自己需要的图元，只需从tern.Shape类继承新类并重写paint()即可（可参考demo目录下的示例）。一个常见的应用场景是基于TernLight开发在线的工作流编辑器，或开发工作流的在线展示功能。
目前，支持的主要能力如下：   
1. 内置支持连线（直角线和直线）;提供了RetangleShape图元；  
2. 支持在图元之间进行连线;(从Shape的Connector上可拉出新的连线)    
3. 支持label，可编辑/显示文本；label可作为Shape等的子元素（见demo中的MyShape示例）；   
4. 支持图元的拖拽；  
5. 支持从画布外拖拽新的shape到画布中（见demo中的示例）；  
![示例图片]( fancimage.github.io/images/ternlight.png )
