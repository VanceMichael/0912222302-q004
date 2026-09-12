# 高原降雨预警接入网关

这是面向业务团队的后端服务，围绕“雨量观测、预警版本、通知记录”提供接口、持久化与审计能力。

## 运行

使用 `docker build -t rain-alert-gateway .` 构建镜像，再执行 `docker run --rm -p 8080:8080 rain-alert-gateway`。服务提供 `GET /health` 检查。
