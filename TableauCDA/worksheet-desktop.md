> 本文是备考经验的总结,尽量讲解进阶知识点,带有主观性  
> 基础课程推荐官方E-learning,learningtableau的模拟题

# 视频讲解
<iframe src="//player.bilibili.com/player.html?aid=427549463&bvid=BV1T341137Qn&cid=748593492&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"  width = 800 height = 600> </iframe>

# 知识点
## 菜单 menu
### file
导出: PPTX,PDF



### Data
Edit data blending relationship: 
- 用处:配置blending匹配关系
- 注意:这里的blending relationship不是relation ship
- data blending relationship的思想: 两个数据源先各自group by聚合,然后再做left join

Date properties: 主要可以修改日期开始时间

Edit Aliaese:  可修改member的alias

export:csv

repalce datasource:切换数据源后,可以再replace reference字段,达到切换字段的目的.


### worksheet
action
- 考点:filter,highlight,url
- this theet就是展示作用该workwheet的action

Tooltips
- 可以展示另外的sheet,传递维度对应的条件
- 注意展示的其他参数

Copy,Export
- 图:png
- 交叉表: xlxs
- 表: .mdb




### Analysis
aggreagate mearuse: 一般是在散点图的时候使用,不进行聚合

stack mark: 对measure value进行堆叠

Percentage of: 就是percent的表计算

Total: 一种table panel的表计算,但是名字就叫做total

trend line: 默认展示一次函数的trend

Forcast: 默认忽略了用于预测维度的最后一个值,目的是防止最后一个时间周期没有过完,数据缺失

Summerize:
- label: 可以用`<computaion>: <value>`的写法,讲讲计算方式
- distribution: 可以设置quantiles

Custom:
- reference line : 一条线
- reference band: 两条线
- distribution band: 区间

### Format
copy paste formating:只针对单个sheet进行操作

### server
user filter
- 控制单个用户的行级权限,控制的用户的维度


## 左侧 data pane
calculation field:Lod,表计算
- https://www.bilibili.com/video/BV1kY411u7iK/?vd_source=b6ef4fa9f0b441d61fedeb95f8202817


Groupby folder,table: 单个sheet是folder,多个数据源是table

Hide unsee field: 隐藏的filed,就不能数据提取.数据提取也有类似的按钮

Create parameter:
1. date type: 除了地理都有
2. display format: 可以更改
3. 参数类型: all list range

pill-default property:最主要是改改数据格式



## 左侧 page filter marks
context filter: 具有优先级,按照顺序执行,本质是临时表

demension filter
- wildcard:注意\*也没有了
- Condition: 可以用度量控制维度,例如过滤出 catgory中 sum(sale) > 10000的

Global filter: 
1. 作用全部sheet
2. 在data source filter显示,甚至删不掉


Marks
- density: 把散点图换成密集程度的显示


Label
- match mark color: 让文字颜色与图形一致

Tooltips
- 工具提示可展示其他sheet


## 上侧 shelf
columns,rows:注意字段,可以对图表的...进行记忆

pill拖入的方式:左键直接拖入,右键拖入可以选择聚合


## 右侧 view
axis
- 增加参考线: 点哪个axis,参考线就在哪个轴上
- 轴的范围: 可右键设置range,tick

