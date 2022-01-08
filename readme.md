# 电子工程训练基地2021年寒假考核任务



## Markdown（All）

> 作为一名优秀的计算机学子，怎么能不会使用或者了解过`Markdown`语法呢？



### 我需要了解什么？

1. 了解`Markdown`的基本语法编写方式，懂得`md`文档的基本写作，能使用它写出一篇比较不错的文档或者博客



### 我需要做什么？

与`git`的学习一起，在`EETB/notes`的仓库下面，创建一个以自己`学号＋姓名首字母缩写`的分支名称，每周写好一篇技术博客，可以说说这周你都学会了什么(不会有人寒假了还每周每周的玩吧，不会吧不会吧)，将写好的 md博客使用`git push`上传到指定分支中



### 相关资料

比较好用的`Markdown`编辑器有 `Typora`(现已经收费)、` Mark Text`等，通过进行相关配置，可以在本地比较快捷方便的编写`Markdown`文档

- [B站教程（仅供参考）](https://www.bilibili.com/video/BV1KZ4y1j7nT)



## git（All）

>  简单的push、commit操作、合并分支、能够查询相关提交记录并进行回滚



### 我需要了解什么？

简单的 `git`操作，能够实现本地 `commit`以及进行远端操作，了解分支操作，能够进行分支回滚



### 我需要做什么？

> 此处内容不会作为考核方式进行出现，它将会和 `Markdown`的文章提交一起作为你每周学习的记录，下面内容只是大致让你了解你需要经历什么步骤

1. 学习 `git`的基础操作，了解本地 `commit`的相关操作流程
2. 在自己的 `GitHub`账户上创建一个仓库，了解并学习如何将自己本地文件 `push`到远程
3. 创建多次提交记录，并形成`dev`与`master`分支，在两个分支下创建提交记录
4. 将两个分支进行合并，并进行两次记录的提交
5. 尝试将分支进行回滚操作



### 相关资料

- [git学习](https://oschina.gitee.io/learn-git-branching/)
- [git的b站教程（不局限于这个）](https://www.bilibili.com/video/BV1Mk4y1y7jR)
- [B站教程](https://www.bilibili.com/video/BV1MU4y1Y7h5)



## 51单片机（21级）

> 了解并熟悉开发板的相关模块的使用，懂得原理图与实物图的转换，能够编写相关代码实现相关功能。



### 我需要了解什么？

1. 熟悉并了解原理图，能够看懂原理图的功能，能够将其与实物图进行结合

2. 熟悉开发板的模块功能，能够通过编写代码使用模块来实现相关功能

3. 了解51单片机的矩阵键盘使用

4. 明白如何使用51单片机的数码管

5. 了解蜂鸣器怎么播放一首好听的音乐

   

### 我需要做什么？

设计一个音乐播放电路，至少可以通过矩阵键盘选择4首歌（一首歌一个按键，另外两个按键功能是分别调到上一首和下一首），
并可以在数码管上显示当前播放歌曲的编号（编码自己随便编，编号由字母与数字组成，如：`E3`），
歌曲可以在蜂鸣器上播放（歌曲不做指定要求）。



### 相关学习资料

- [51单片机学习视频及板子原理图（基地网盘）](http://pan.eetb.space/index.php/s/pHBiPxadNdRgTDT)
- [51单片机视频教程（云OSS）](https://dpj-21.oss-cn-beijing.aliyuncs.com/C51%E7%9A%84%E8%A7%86%E9%A2%91%E6%95%99%E7%A8%8B.zip)







## Nano嵌入式系统开发（20级）

>  学习查看文档的能力、GPIO PWM调节LED灯、简单的linux相关命令、python、Linux的目录了解，yolofast跑起来一个识别小程序`基于机器视觉的手势识别(毕设题目)`



### 我需要了解什么？

1. 你需要了解如何在`Linux`下查询相关相关命令，了解它的相关功能
2. 你需要掌握如何在`Linux`中使用命令行进行基本操作，懂得如何进入一个文件，如何编辑相关系统文件
3. 拥有相关`python`基础，能够编写相关`python`代码实现相关功能，能够通过PWM控制LED灯亮度
4. 尝试了解`volo-fast`的相关代码，争取了解相关原理，尝试运行相关模型



### 我需要做什么？

搭建并且初识`Nano`以及相关`Linux`的操作，搭建好`volo-fast`代码框架，并通过该框架来调用外接摄像头模块，从而实现 `基于机器视觉的手势识别`

代码种类不限，可 `C`可 `python`

实现内容：通过在 `nano`中 使用 `yolo-fast`建立一个小模型，能够实现对手势的识别以及做出相关反馈

完成任务：搭建模型库，并进行训练，使其能够实现检测手势形状例如”OK“、”张开手掌“这两种手势。 同时在命令行中输出识别结果与置信度



### 相关学习资料 

- [python数据分析](https://github.com/iamseancheney/python_for_data_analysis_2nd_chinese_version)
- [ 廖雪峰老师的网站](https://www.liaoxuefeng.com/wiki/1016959663602400/1183249464292448)
- [voloV5的b站学习视频](https://www.bilibili.com/video/BV1YL4y1J7xz?spm_id_from=333.999.0.0)
- [nano搭建以及配置环境](https://blog.csdn.net/u011119817/article/details/109622480)



# 其他

## 关于博客以及博文

养成一个编写博客的习惯是非常好的，它可以帮你记录你在学习过程中遇到的点点滴滴，并且当此类问题再次发现的时候，你能够很快的找到相关的解决方法，这会极大的提升你的学习效率，并且博客搭建在现如今也是比较简单以及快捷的，在你学习完`git`以及`markdown`的相关书写后，你可以使用`GitHub`or `Gitee`这两个平台来搭建一个属于自己的博客页面（例如我的[ZHYCarge的博客](zhycarge.github.io)）



## 提问的艺术

当你在学习的过程中，遇到了些许问题的时候，不要急着去询问学长学姐，请先尝试从必应或者相关博客中去寻找答案，详情请阅读"[提问的艺术](https://github.com/GUET-EETB/How-To-Ask-Questions-The-Smart-Way/blob/main/README.md)",这并不是我们不想帮你及时解答问题，而是我们需要培养你们自身的寻找问题的能力。在以后的学习以及工作中，我们总会遇到种种问题，但是如果你一旦遇到问题就去询问学长or前辈，那么你会渐渐对其形成依赖，从而丧失自身搜寻问题的能力。但以后的路，并不是都会有“领路人”来带着你前行不是吗？因此，学会独立思考以及学会自我搜索答案是个很重要的一次过程。



# 尾言

上学的时光悄然而逝，我们即将离开学校，回到家中，相信你会牢牢把握这个假期，通过这个假期好好的丰富自己的知识面，让自己的兴趣得到充分增长~
