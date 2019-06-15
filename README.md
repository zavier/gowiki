# Writing Web Applications 代码

## 使用Golang实现创建web应用

原文连接：[https://golang.org/doc/articles/wiki/](https://golang.org/doc/articles/wiki/)

简单的增删改查
1. 编辑保存会存储为同名的txt文件
2. 查看时读取对应文件，显示到页面，如果不存在则进入编辑页面

## 使用

### 启动 main 方法

### 编辑页面
```
文件不存在则进入编辑
http://localhost:8080/edit/【文件名(不包含后缀)】
demo: http://localhost:8080/edit/test
```

###浏览
```
http://localhost:8080/view/【文件名(不包含后缀)】
demo: http://localhost:8080/view/test
```
