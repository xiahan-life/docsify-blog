> 本文是备考经验的总结,尽量讲解进阶知识点,带有主观性  
> 基础课程推荐官方E-learning,learningtableau的模拟题

# 视频讲解
<iframe src="//player.bilibili.com/player.html?aid=470039837&bvid=BV17T411G77Z&cid=748593555&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width = 800 height = 600> </iframe>


# 知识点
## connetion pane 左侧
connection
- 可以混合数据源


## 上侧图表区
parameter
- 范围:只有all,range,没有list
- data type: 相对desktop 少了日期
- 作用: 替代文本信息,比如导入文件,写SQL



## 下侧操作区

### input
mutiple file
- wildcard用的\*做匹配

### clean
filter value:  作用单行,返回布尔值

- Romove filed:  移除这个字段

- Hide filed: 只在output的时候显示这个字段,过程都不展示这个字段

data role:
- 作用: 看数据是否符合格式
- custom data role: 引用cloud上面的data role,cloud的data role是在prep中自定义发布上去的
- publish data role: 应该可以发布,但是我没有成功过

clean:
- 统一大小写
- 去除letter:字母
- 去除number
- 去除punctuation: 去除标点符号
- 三种去除空格
    - trim space: 删除两侧的空格
    - remove extra space: 删除两侧的空格,中间的多个空格,替换成单个空格
    - remove all space:如题

group: 相对desktop多增加了3个操作
- manual selection: 手动选吧.
- pronuncitaion(发音): 通过发音去聚类,这个做法是第一次见到
- Spelling(拼写): 通过拼写的方式去聚类
- commmon characters: 将有相同的字母,数量的词,聚类在一起. 


### new rows
- 作用: 填补filed中的空缺值,具体看视频


### 其他知识
https://www.bilibili.com/video/BV1Ef4y1275K?spm_id_from=333.337.search-card.all.click