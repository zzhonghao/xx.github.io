# xx.github.io
## CV学习记录  
### 练习写博客，记录学习进度  
学习了markdown语法：  
  怎么添加标题，如何换行等  
入门了github  
  如何建立自己的仓库  
### 熟悉比赛题目并理解赛题  
#### 赛题数据
本次比赛采用的是街道字符数据，每张图片已经给出了标签：  
左上角坐标X top
字符高度 height  
左上角坐标Y left  
字符宽度 width  
字符标签 label
#### 评价指标  
score = 识别正确的图片数量/测试集图片数量  
#### 相关解题思路  
官方提供了几种解题思路  
由于每张图片的字符数量不一致，对识别造成一定难度  
1.定长字符，固定长度。  
2.利用CNN中的字符识别模型  
3.根据图片中字符的位置，利用物体检查原理  
#### 跑通baseline  
初次接触CV，研究baseline遇到许多问题  
1.pytorch环境安装与配置  
  下载过程中报错  
  显卡驱动安装中出现不适配  
2.baseline读取数据  
  文件路径出错
  baseline中的代码参数需微调(改num_work等)  
baseline中还有许多地方依旧不明白，期待在后续的学习过程中理解透彻  
### 总结
本次入门CV，收获许多，第一次接触CV，pytorch等等。
自己收获颇多，期待在后面的学习过程中更加深入这一领域  
