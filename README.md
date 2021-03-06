# 半小时快速上手golang web编程之用户的增删改查(示例代码)
博客教程页面: https://segmentfault.com/a/1190000020871866  
在线体验地址: [http://gorose-gin.fizzday.net:8080/](http://gorose-gin.fizzday.net:8080/)  

## 说明
本实例快速实现一个用户的增删改查, 采用前后端分离模式, 后端采用`gorose orm` + `gin`框架完成api的开发, 前端使用`原生html+jquery+ajax`交互数据. 

## 安装和启动

- 手动
```shell script
git clone https://github.com/gohouse/goroseGin.git
cd goroseGin
go mod tidy
go run main.go
```
> 注意: 确保系统已经安装了golang运行环境和vgo,才能正常执行  

- docker  
```shell script
docker run -d -it --rm -p 8080:8080 ababy/gorose-gin sh -c "go run main.go"
```

> 注意: 手动和docker, 两种方案, 二选其一即可, 建议使用docker运行, 一键运行, 不需要处理环境问题  

## 运行查看效果

访问 [http://localhost:8080](http://localhost:8080) ,就可以完成用户的增删改查操作了,效果图  
![gorose-gin.png](https://i.loli.net/2019/10/31/B7wkU8XYS6OIRdH.jpg)
