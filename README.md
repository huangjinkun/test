# 数据库文档

<a name="返回顶部"></a>

## 数据表列表

* [ai_ability_record()](#ai_ability_record_pointer)

* [ai_likehood()](#ai_likehood_pointer)



## 数据表说明

<a name="ai_ability_record_pointer"></a>

* ai_ability_record表()[↑](#返回顶部)

|字段名称|字段类型|字段含义|
|:---:|:---:|:---:|
|rid|bigint(20)|记录编号|
|tcode|varchar(50)|图谱编号|
|ncode|varchar(50)|知识点编号|
|stuid|varchar(50)|学生编号|
|ability|varchar(20)|能力值|
|ability_prop|varchar(50)|能力评估信心值|
|likelihood|text|概率值集合|
|curriculum_id|varchar(50)|课次编号|
|createtime|timestamp|创建时间|
|qnum|bigint(20)|题目数量|
|sys_code|varchar(25)|系统编号|
|session_id|bigint(20)|流程编号|
|stage|varchar(25)|过程阶段编码|
|ext_1|varchar(255)|扩展字段1|
|ext_2|varchar(255)|扩展字段2|
|ext_3|varchar(15)|扩展字段3|

<a name="ai_likehood_pointer"></a>

* ai_likehood表()[↑](#返回顶部)

|字段名称|字段类型|字段含义|
|:---:|:---:|:---:|
|id|int(11)||
|session_id|bigint(20)|会话编号|
|mcode|varchar(50)|图谱编号|
|ncode|varchar(50)|知识点编号|
|likehood|text|概率数据|
|ctime|timestamp|创建时间|
|utime|timestamp|更新时间|

