# tabtoy



# 流程
并发读取电子表格及缓存

内建Type表读取
内建Data表读取

Index表导入
Type表导入
Data表导入

Data表 数组表头 合并


KV表转Data表

键值优化压缩

json导出
go源码导出

# 检查


# TODO

统一的打印输出

所有Meta功能实现，RepeatCheck



索引代码生成

基于map[string]interface{}的二进制支持


数组的处理： 单元格空时，无论任何情况，导出数组中都没有数值和0填充，除非添加一个特性：强制填充默认值，数组通过多个单元格导出时，默认值为单元格数量

做成SDK，无需导出数据，开发期直接读取电子表格

KV键值表合理的换行