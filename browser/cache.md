## 缓存
编程两大难题：缓存失效和命名

### 强缓存
用户发送的请求直接从客户端的缓存中获取，不发送到服务器；

### 协商缓存

用户发送的请求，发送到服务器后，由服务器判定是否从缓存中获取资源


### 请求头

- Expires
- Cache-control