发布日期    | 2019-12-24 
---------|------
史诗名称     | 智能毕业纪念相册APP
文件现状     | 已完成 
文件主人     | 莫欣妹 
领头的设计师 | 莫欣妹 
领头的开发者 | 莫欣妹  
领头的测试者 | 莫欣妹 



## （一）加值宣言

目前，市场上许多相册APP的功能仅仅只是储存照片的，对于如何帮用户更好的查找和整理照片的痛点并没有提供很好的基础服务。但是随着人工智能的发展，针对如何帮用户更好的查找和整理照片的痛点，百度API可以提供智能的帮助，现将采用百度通用物体和场景识别和地标识别API对现有产品进行加值和优化。主要运用机器学习中的通用物体和场景识别功能，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的物体及场景标签。辅助：还运用了地标识别功能，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的地标识别结果。

## （二）核心价值宣言（最小可行性产品）

着眼于用户的最基本需求，帮助用户解决如何更好的查找和整理照片的问题，给用户提供便捷管理照片的最基础服务。

## （三）用户痛点宣言

**背景：**

随着时代的发展，现在越来越多的人喜欢用拍照的方式来记录生活的点点滴滴了。但是，由于人们都喜欢用拍照的方式来记录生活，所以照片也越来越多，有时候想在相册中找到一张自己想要找的那张照片时，要花费很长时间才能找到，因为照片很多；同时，照片繁多，找的时候眼花缭乱，很容易就造成视觉疲劳，就没有耐心找下去了。所以，能够帮助用户提供一个更好的查找和整理照片的最基础服务，是为喜欢用拍照方式记录生活的用户提供最好的帮助。

**用户：**

喜欢用拍照方式纪念生活点点滴滴的用户

**目的：**

开发一个用智能方法管理用户相册的智能纪念

**用户痛点：**

- 场景一：小明想在手机相册中找到初中毕业时和好朋友小莫拍的一张合照，但是手机图库中的照片实在太多了，一张一张的滑动找实在太浪费时间了。
- 场景二：小红想要把手机图库中的照片按照分类来管理，以方面自己在需要再找某一张照片的时候可以很快的锁定自己想要的那张照片，但是手机相册并没有这个功能。
- 场景三：小李在相册中看到了一张初中时期拍的一张照片，图片是学校的某一处地标位置，但是时间过去有点久了，一时间想不起来是哪里，有点苦恼。


## （四）AI概率性考量

- 百度通用物体和场景识别技术，有三大保证：

1. 准确性高：基于百度海量数据，利用深度学习技术及高精度算法不断迭代模型，准确率业界领先，识别准确率超过99%。
2. 标签体系丰富：可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务。
3. 简单易用：支持标准化接口封装，调用简单，只需上传单张图片，即可获取识别结果。

- 所以，该产品利用了图像识别中的通用物体和场景识别技术，可以对繁多的照片进行智能的分类，帮助用户更好的管理相册。百度通用物体和场景技术不仅识别准确率较高，而且可识别出10万+物体及场景标签，支持标准化接口封装，调用简单，只需上传单张图片，即可获取识别结果，普遍情况下都可以使用。该产品因环境因素或者拍照造成识别不准确的状况，概率较小为少数事件，对正面影响并不大。


## （五）需求列表

用户案列 | 对应标题 | 重要程度
----|------|----
某同学希望某节课上的考勤是可以快速完成，同时减少考勤错误的发生 | 人脸识别  | 重要
老师想要知道哪位学生考勤作弊了并逃课了 | 人脸识别  | 重要
老师想知道哪位同学考勤失败了 | 高德地图API  | 次重要 

**具体应用场景**

1. 上课时，老师要进行课堂考勤，老师觉得如果用一个一个名字念过，学生答“到”的方式考勤的话太浪费时间了。但是，老师发现最近有一个小程序可以帮助她高效率完成课堂考勤过程。于是叫同学拿出手机，打开人脸考勤小程序，让所有同学在人脸考勤小程序上通过人脸识别同时考勤，快速完成了课堂考勤。
2. 在上课的时候老师看到来上课的同学人数很少，进行了课堂考勤，然而课代表点完名后发现答“到”的人数比来上课的人数多了十几个。因为老师并不认识全部学生，所以并不知道哪位学生考勤作弊了。但是，老师发现最近有一个小程序可以帮助她很快找出考勤作弊的学生，于是叫学生打开人脸考勤小程序，快速完成了考勤，查看了考勤记录发现了考勤作弊的十几个学生是谁。






 
