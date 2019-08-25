# Gin + Gorm 的 RESTful 实例

安装依赖:
```
go mod tidy
```

编辑 config/config.yaml 配置数据库:
```
dsn: "root:123456@tcp(127.0.0.1:3306)/admin?charset=utf8&parseTime=True&loc=Local"
```

运行：
```
go run main.go
```