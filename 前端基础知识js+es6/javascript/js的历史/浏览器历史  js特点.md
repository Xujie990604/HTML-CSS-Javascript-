# 浏览器历史

1993 Mosaic是互联网历史上第一个获得普遍使用的浏览器
1996 javascript问世
浏览器组成部分
    1.shell外壳
    2.内核
      渲染引擎
      js引擎
      其他模块
2001 ie6实现对js引擎的优化和分离
2008 Google 更加优化

编译语言： 先通篇翻译之后，执行翻译完的文件。
     c c++   速度快 用于底层实现，游戏     移植性不好 

解释语言： 看一行翻译一行执行一行（不需要生成别的文件）
     php js   速度稍微慢一点 稳定性极高    跨平台（极大的优点）

java 先编译后解释 因为java虚拟机的存在
    .java ----java c --编译--.class--jvm(虚拟机)--解释执行

js特点
    1.解释语言
    2.单线程（论转时间片，类似于吃饭）
    3.ECMA标准 js原生也称为ECMAScript
        js三大阶段：ECMAScript + DOM + BOM（后两个由浏览器提供）