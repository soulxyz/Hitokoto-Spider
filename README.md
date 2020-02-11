# Hitokoto-Spider
这个项目是与一言的库相关的项目，一直想用python来爬取一言的文本库，所以就有了这个项目。
本项目正在开发，需要用到requests库（访问API）、panda(Csv读写)或xlrd&xlwt(Excel读写)，第一次使用请输入
```bash
$ pip install requests
或
$ pip install requests（xlrd xlwt）
``` 
来安装所需要的python库！爬取的链接为：https://v1.hitokoto.cn/ 或 https://international.v1.hitokoto.cn/	 后者QPS限制25 前者QPS限制10 

# 进度一览
- [x] 获取一言内容
- [ ] 导出为csv文件
- [ ] 自动分类一言类别
- [ ] GUI支持
 [ ] 导出为xls文件
