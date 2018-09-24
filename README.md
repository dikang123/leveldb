# leveldb

### 简介
leveldb是一个Key-Value数据库。因为其优秀的性能，被广泛地应用。该项目主要是一个简单的工具，该工具提供leveldb的创建，数据导出和导入。

### 下载

**建议下载最新版本**

|版本     |支持平台|链接|
|--------|---------|----|
|leveldb v1.1|Linux, Windows, Mac OSX|[下载](http://devtools.qiniu.com/leveldb-v1.1.zip)|

### 使用
该工具支持leveldb的创建，数据导入和数据导出，以及数据条目的数量计算，所以一共有4个命令。


|命令|描述|示例|
|------|---------|--------|
|create|创建leveldb数据库|leveldb -create '/Users/jemy/Data/test' |
|import|导入数据到leveldb|leveldb -import '/Users/jemy/Data/test' -data '/Users/jemy/Data/test.txt' |
|export|从leveldb导出数据|leveldb -export '/Users/jemy/Data/test' >> test.dat|
|count|计算leveldb数据条目数量|leveldb -count '/Users/jemy/Data/test' |

备注：
基于工具的简单性，导入的数据文件按行格式为key`\t`value，导出的内容为key`\t`value。不支持其他的分隔符。

### 帮助
如果您遇到任何问题，可以加QQ：2037014430，我将乐意帮助您，非技术问题勿扰。
