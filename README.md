# elastic-sql-api
rapid config to create api from  elasticsearch to another APP,simple to write sql to ini file.
Elasticsearch快速生成api引擎，通用需求，不用写代码，仅仅用sql在配置文件里配置，就可以为外部数据调用生成api数据调用接口。

# feature:
##  1.支持支持多人协作，每人单独配置文件
## 2.自动为配置文件每个section生成http调用url进行调用
## 3.每个调用接口支持一个或多个sql进行结果汇集
## 4.可以根据规则，对查询参数自动聚合成sql条件,进行查询
## 5.支持对每个sql进行xpath配置，自动构造返回json结果集
## 6.支持自定义参数传递形成要选取的查询列
## 7.可以自定义插件支持es原生查询
## 8.自带通用插件支持子查询,subquery
## 9.支持对查询slow的sql进行分析，优化

