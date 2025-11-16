[English](README.EN.)
 # 知识库助手

配置文件说明

```json
{
  //日志配置
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  //模型配置,openAPI支持
  "ModelConfigs": [
    {
      "Model": "deepseek-chat",
      "Endpoint": "https://api.deepseek.com/v1",
      "ApiKey": ""
    },
    {
      "Model": "deepseek-reasoner",
      "Endpoint": "https://api.deepseek.com/v1",
      "ApiKey": ""
    }
  ],
  //向量模型配置
  "EmbeddingModel": {
    "Model": "Qwen/Qwen3-Embedding-0.6B",
    "Endpoint": "https://api.siliconflow.cn/v1/",
    "ApiKey": ""
  },
  //端口号，默认启动在http://localhost中
  "Port": 47122,
  "AllowedHosts": "*"
}
```



运行截图

![截图1](./doc/Snipaste_2025-09-17_14-57-29.png)
![截图2](./doc/Snipaste_2025-09-17_14-57-40.png)
![截图3](./doc/Snipaste_2025-09-17_14-57-09.png)
![截图4](./doc/Snipaste_2025-09-17_14-57-51.png)



