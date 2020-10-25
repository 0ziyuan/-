大一Java选修结课作业，很粗糙，有时间又优化

#### 项目描述

从文本文件中读取试题显示出来，然后让用户来回答，然后把答题内容保存为数据文件，并给出相应的分数。

扩展了倒计时功能，并采用逐题分页做答，以提升GUI界面的美观友好及使用体验。

#### 使用操作

##### 程序运行

将压缩包解压后，打开文件夹“问卷系统”，可先将文件夹“源文件”下的源文件进行编译，再运行；也可直接运行文件夹“字节码文件”下已编译生成的字节码文件。其中，main方法在Test2.java中，“题目.txt”为程序运行时读取题目的文件。

##### 答题

程序运行成功后，点击“开始考试”，显示题目的同时，倒计时开始。点击“A”“B”“C”“D”进行选择，点击“上一题” “下一题”进行题目切换，点击“提交考试”进行答案提交，系统随即批改显示对几道﹑错几道和分数。

若倒计时结束时，仍未提交考试，则自动结束作答，并提示“考试结束”。

#### 当前效果

##### 开始运行

![开始运行](https://gitee.com/wanli-0ziyuan/gitee-graph-bed/raw/master/img/20201025141847.png)

当在第一题时，点击上一题按钮

![当在第一题时，点击上一题按钮](https://gitee.com/wanli-0ziyuan/gitee-graph-bed/raw/master/img/20201025141938.png)

当在第十题时，点击下一题按钮

![当在第十题时，点击下一题按钮](https://gitee.com/wanli-0ziyuan/gitee-graph-bed/raw/master/img/20201025142023.png)

点击“提交考试”

![点击“提交考试”](https://gitee.com/wanli-0ziyuan/gitee-graph-bed/raw/master/img/20201025142050.png)

#### 最终目标

1. 从题库中随机选题生成问卷；
2. 实现账户登陆，成绩存档；
3. 菜单栏添加“帮助”；
4. GUI美化。