JNUMasterThesis v0.0.1
==============================
暨南大学硕士学位论文LaTex模板 0.0.1
==============================

目前提供的功能
--------------------------------------------
1. 基本实现了暨大毕业论文要求规范
2. 定理、引理等的中文化
4. 算法环境的中文化，算法默认使用algorithm2e
5. 图表的中文化
6. 提供对bib的支持，省去文献管理的麻烦
7. 简单使用实例的书写

本模板为非官方模板，最终权利和解释权归原作者和[数据存储与集群计算实验室](http://dsc.jnu.edu.cn)所有。

可以随意修改本模板功能，请保留原作者信息^_^

如果您在使用过程中发现Bug可以随时联系原作者修改完善y.t.zhou@foxmail.com

使用样列请参考源码包中的PDF，源码包不提供基本的LaTex入门教程。如果您在使用过程需要基本的LaTex入门，请参考LaTex手册或者下面列出的资料。

本模板制作过程参考了《一份不太简短的LaTexe介绍》《LaTexe用户手册》《用LaTex写漂亮的学位论文》在此感谢以上作者辛勤的付出，包括其它网络资料的作者。
主要参考的链接如下：
1. http://blog.sina.com.cn/s/articlelist_1578561911_0_1.
2. http://kb.mit.edu/confluence/pages/viewpage.action?pageId=3907168
3. http://blog.csdn.net/xyqzki/article/details/6934729

源码目录结构
--------------------------------------------------------
Related papers
--------------
1. bib目录：bib文件存放目录，目前内容是本人常用的论文.
2. chapter目录:
    > a) declaration.tex：第一页论文信息，第二页独创性声明、学位论文授权使用书.
    >
    > b) abstract.tex: 中英文摘要. 
    >
    > c) chap1.tex:第一章.
    >
    > d) chap2.tex: 第二章.
    >
    > e) conclusion.tex: 结论.
	>
    > f) paperList.tex: 攻读学位期间发表的论文.
	>
    > h) acknowledgement.tex: 致谢.
3. img目录：图片存放目录.

运行环境
---------------------------
Win8, CTex(2.9.2),WinEdt7.0下编译生成成功。
[ctex](http://www.ctex.org/HomePage)

编译生成步骤
----------------------------
LaTex->B->LaTex->LaTex->div/pdf


致谢
---------------------------
在此首先感谢邓玉辉教授给我们提供宽松的科研的环境，同时也要感谢谢俊杰师兄教会我使用LATEX2ε，另外感谢刘瑞锴、杨儒、刘冰星、甘顺仪等小伙伴的帮助，最后感谢实验室及其班里其他同学的帮助和支持。

Author
-------------------
Yongtao Zhou
Email: y.t.zhou@foxmail.com
