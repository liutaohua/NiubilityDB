# niubilitydb
&emsp;&emsp;实现一个简单的分布式数据库模型，包含基本的 KV 存储，以及 raft 算法实现等，边写边学,边学边写。

## 背景
&emsp;&emsp;自己在工作初期，有幸接触到了对象存储，有幸结识了一帮大神，从此对 nosql 领域甚是喜欢，
从阅读 Dynamo 论文开始，就像着了魔一样，幻想将来有一天能够有机会从事 nosql 领域的相关开发，事与愿违，
总之没能有幸进入这个领域，甚是遗憾，所以自己最终决定，抽出自己的闲暇时间一步一步实现一个简易的数据存储，
之后完成一个分布式的模型。

## 近期计划
| 版本 | 计划 | 
| ------ | ------ | 
| 0.1.0 | 完成基本的存储结构 | 
| 0.2.0 | 添加多种存储格式支持 |
| ------ | ------ |

## 开发进度
目前版本定义为V0.0.1，完成功能：
1. 存储node节点到文件
1. 使用mmap存储映射
1. 分离了之前的Node为Internal和Leaf
1. 增加了对K,V的类型限定为DataHolder

TODO:
1. 增加测试
1. 优化不合理的同步(至硬盘)
1. 更详细的文件格式描述及blog
1. 准备大方向的架构设计

## 其它
* 欢迎大牛批评指正
* 欢迎有兴趣的朋友一起
* 有任何问题请开 issue 或直接与我联系。

## 联系方式

&emsp;Blog: liutaohua.github.io

&emsp;Email: 13965645@qq.com

&emsp;<strong>别问我为什么用 QQ 邮箱，因为可以直接加 QQ</strong>
