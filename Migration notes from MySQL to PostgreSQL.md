# 从MySQL迁移到PostgreSQL杂记 Note of migration from MySQL to PostgreSQL

##### 1. 使用 mysqldump+psql 命令行组合并不好用, 即使 MySQL5.7 版本可以使用 --compatible=postgresql 参数但是导出的文件依然不可用，除非导出的文件经过自制脚本把语句转换掉，但是需要开发成本，两者在语句上的差异可以参考这篇CSDN的文章-[超全mysql转换postgresql数据库方案](https://blog.csdn.net/weixin_42303757/article/details/128896250)
##### 2. 网上使用较多的是pgloader来转换但是缺少官方中文教程，[官方英文教程](https://pgloader.readthedocs.io/en/latest/index.html)读起来有点花时间 !_!
