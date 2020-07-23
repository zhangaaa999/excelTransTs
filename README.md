# excelTransTs
博毅创为cocoscreator课程 MVC框架中，EXCEL文件转换成TS文件的小工具，python3实现

## 使用流程
### python3环境搭建
1. 安装python3（具体安装过程自行百度）
2. 进入python3环境，安装依赖库`pandas`
```
pip install pandas
```

### 创建2个文件夹Excels和Ts
将需要转换的文件，放到Excels中。
注意：
1. 所有文件必须是.excel后缀的；
2. 文件的格式，必须要和课程中提供的格式一致（第一行是字段名，第二行是字段类型名，从第三行开始是数据）；

### 运行脚本
```
python excelTransTs.py
```
运行完成以后，会在Ts文件夹中，生成对应的ts文件；
