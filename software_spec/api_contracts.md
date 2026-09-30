# 系统输入输出与跨服务 API 契约规范 (API Contracts)

## 一、核心接口清单 (Endpoints)
- `POST /api/v1/mindmap/execute`: 触发全流程执行
- `GET /api/v1/mindmap/status`: 查询执行状态

<!-- API_CONTRACTS_SPEC_START -->
```json
{
  "endpoints": [
    {
      "path": "/api/v1/mindmap/execute",
      "method": "POST",
      "auth": "Bearer"
    },
    {
      "path": "/api/v1/mindmap/status",
      "method": "GET",
      "auth": "Bearer"
    }
  ]
}
```
<!-- API_CONTRACTS_SPEC_END -->
