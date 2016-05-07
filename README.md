### Python 标准目录结构说明

#### 顶层目录包含

- README.md

	项目信息，层次结构说明
	
- requirements.pip

	项目依赖库(版本号)
	
- test-requirements.pip

	测试依赖库（版本号）

- setup.py

	使用distuitls工具进行分发（安装）的脚本标准名称
	
#### bin

	存放distutils生成的二进制文件
	
#### docs

	存放项目文档
	
- conf.py

	定义工程运行的配置信息

- quickstart.rst

	详细说明工程运行的方式
	
- index.rst

	说明文档的目录索引
	
#### data

	存放项目中依赖的一些文本数据源，或者数据库建表语句等
	
#### etc

	存放工程配置文件的样例

#### tools

	存放启动脚本，调试脚本等
