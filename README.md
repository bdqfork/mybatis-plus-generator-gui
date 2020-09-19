mybatis-plus-generator-gui
==============

mybatis-plus-generator-gui是基于[mybatis-generator-gui](https://github.com/zouzg/mybatis-generator-gui)开发的适用于MybatisPlus的一款界面工具, 本工具可以快速生成MybatisPlus的Java POJO文件及数据库Mapping文件。
使用方式与mybatis-generator-gui一致。


### 核心特性
* 按照界面步骤轻松生成代码，省去XML繁琐的学习与配置过程
* 保存数据库连接与Generator配置，每次代码生成轻松搞定
* 内置常用插件，比如分页插件
* 支持OverSSH 方式，通过SSH隧道连接至公司内网访问数据库
* 把数据库中表列的注释生成为Java实体的注释，生成的实体清晰明了
* 可选的去除掉对版本管理不友好的注释，这样新增或删除字段重新生成的文件比较过来清楚
* 目前已经支持Mysql、Mysql8、Oracle、PostgreSQL与SQL Server，暂不对其他非主流数据库提供支持。(MySQL支持的比较好，其他数据库有什么问题可以在issue中反馈)


### 注意事项
* 本自动生成代码工具只适合生成单表的增删改查，对于需要做数据库联合查询的，请自行写新的XML与Mapper；
* 部分系统在中文输入方法时输入框中无法输入文字，请切换成英文输入法；
* 如果不明白对应字段或选项是什么意思的时候，把光标放在对应字段或Label上停留一会然后如果有解释会出现解释；
* 本项目基于mybatis-generator-gui开发，请大家支持原作者。

### 文档
更多详细文档请参考原作者的Wiki
* [Usage](https://github.com/astarring/mybatis-generator-gui/wiki/Usage-Guide)
