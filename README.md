# CORS Proxy for API

这是一个 Cloudflare Pages Functions 代理，用于解决浏览器 CORS 跨域问题。

## 使用方法

POST 请求到此代理，body 格式：
```json
{
  "apiKey": "你的API密钥",
  "body": {
    "model": "gemini-3-pro-all",
    "messages": [{"role": "user", "content": "hello"}]
  }
}
```
