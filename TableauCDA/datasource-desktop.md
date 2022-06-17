> 本文是备考经验的总结,尽量讲解进阶知识点,带有主观性  
> 基础课程推荐官方E-learning,learningtableau的模拟题

# 视频讲解
<iframe src="//player.bilibili.com/player.html?aid=642500417&bvid=BV11Y4y1G71Q&cid=748593609&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width = 800 height = 600> </iframe>

# 知识点
## 顶部:data menu
### Data
Export data as csv: 数据是可以导出为csv. 其实也只是数据能够导出csv.导出对应的sheet


Eidt data source filter: 
1. Global Filter: 作用sheet的Demension,也作用在data source 之中
2. condition filter似乎不能引用参数



### Server
sign: 要选择site.

open workbook: 就是选择有权限的workbook,并且是在site中

Publish data source: 看看混合数据源能否拖动
**


## 左侧:side bar
Custom sql:
1. SQL是可以写Join的
2. 也可以加参数

New Union
1. 匹配方式: 可以用通配符
2. 手动拖动在物理层进行

data interpreter
- 作用:将空行,合并的excle,整理为结构化的数据
- 红色: 表示解释为header
- 绿色: 表示解释为value

## 顶部:表关系
live connection:  好像直接连接就行了

Extract connection: 
- Data Storage: 其实也没有太搞明白,逻辑表可以进行聚合,物理表可以增加性能
- filter: 实际上就是data filter
- Aggregation: roll up视图中的的维度,见图
- Number of Rows: 要么抽行数,要么抽字段


物理层:
- Join: 
  1. 不能够引用现有的计算字段
  2. 没有leftOnlyJoin
- Union: 注意放置在下方

逻辑层:relationship
- 思想: 让Join的表始终在view中展示完备数据
- https://www.bilibili.com/video/BV1MZ4y157Dq?spm_id_from=333.337.search-card.all.click


## 下部:field
group: 其实是手动创建的group. 这里注意与prep不同.

calculation filed: 创建了不用到Join

Split: 只能够切一次

Custom split: 可以一次切出多个字段






