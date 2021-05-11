一本糊涂账
=========
</br>
</br>

## 一、功能一览

###  1、消费一览

统计本月的消费总数，今日消费，日均消费，本月剩余，日均可用，距离月末有多少天。

同时使用一个环形进度条，这个环形进度条不是JDK自带的，需要自己设计，并且随着消费用度，颜色从绿色渐变为红色。

![消费一览](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2742.png)

### 2、记一笔

记录本日的消费额度， 分类下拉框从 消费分类数据中读取，并且把经常消费的分类放在前面。
 
日期默认选中今天，也可以手动指定日期。 

![记一笔](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2743.png)

### 3、消费分类管理

对消费进行经典的CRUD 增删改查管理，同时显示一个分类下的消费次数。

这里涉及到多表关系：
消费记录和消费分类是多对一关系。

![消费分类管理](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2744.png)

### 4、月度消费报表

使用第三方chart类生成柱状报表，显示本月的消费趋势。

![月度消费报表](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2745.png)

### 5、设置预算和数据库路径

在消费一览中需要显示本月可能多少金额，都是建立在预算的基础上的。

在设置页面，设置本月的预算金额。

后续的还原和备份，都需要用到数据库的命令mysql和mysqldump，需要在这里配置mysql的安装目录 

![设置预算和数据库路径](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2746.png)

### 6、备份数据

把数据库中的所有数据，备份到.sql文件中 

![备份数据](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2747.png)

### 7、恢复数据 

根据.sql文件还原数据库 

![恢复数据](https://github.com/T233HAO/hutubill/blob/main/img/how2j-image/2748.png)

