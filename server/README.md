# README

```text

api/            API
    v1	        v1版本接口
cmd/
config/         配置包(config.yaml对应的配置结构体)
constant/       常量
core/           核心文件
docs/           swagger文档目录
global/         全局对象
initialize/     初始化(路由,redis,gorm,验证器的初始化)
log/            日志
middleware/     中间件
model/          结构体层(模型对应数据表)
    request	    入参结构体(接收前端发送到后端的数据)
    response	出参结构体(返回给前端的数据结构体)
packfile/       静态文件打包
resource/       静态资源文件夹
router/         路由
service/        服务(存放业务逻辑问题)
uploads/        上传文件路径
utils/          工具包(工具函数封装)
    upload	    oss(oss接口封装)





```