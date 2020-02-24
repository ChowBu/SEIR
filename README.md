## github原地址 

https://github.com/zwdnet/2019-nCov-SIRmodel

## 疫情预测模型

在airticle.png 中
文章出自《传染病动力学的数学建模与研究》
改善的模型也在这篇文章里面

## 程序的坑

1. 注释里计算好的S0，beta 使用的是前21天的数据，
但是预测的模型数据是总共43天的，两者数据不一致

2. 使用43天的数据无法计算S0，beta

## 关于注释中的代码

注释里面的代码是计算参数的，大家可以去掉注释跑一下，里面计算S0，beta的时候只能使用csv的前21条数据，注释去掉后代码无法运行的，可以联系我

## 鸣谢 
感谢作者的代码zwdnet,虽然很多参数，没有完全使用公开数据计算，但是作者为了预测查询了很多专业的医学数据，做了很多，很多工作。而且作者本人是个医生，为了写代码付出了很多劳动
