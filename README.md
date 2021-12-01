# docsify-demo
[如何使用docsify搭建文档类型的网站](https://mp.weixin.qq.com/s/TPXHaTdfTYKrcpm77gPHyA)

### JavaGuide
- 在线阅读地址：https://snailclimb.gitee.io/javaguide-interview/#/cd
- Github：https://github.com/Snailclimb/JavaGuide-Interview
- 码云：https://gitee.com/SnailClimb/JavaGuide-Interview


本地预览
通过运行 docsify serve 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 http://localhost:3000 。

docsify serve docs



nodejs编写docsify自动遍历当前目录下md文档生成_sidebar.md  
1. 在docsify文档目录（比如：docs）下，创建genSidebar.js，拷贝下面的代码到genSidebar.js中保存；  
2. 执行下面的node命令即可生成：_sidebar.md
node genSidebar.js