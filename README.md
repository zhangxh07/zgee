### 测试示例

```
% curl "http://localhost:9090/hello?name=geektutu"
hello geektutu, you're at /hello

% curl "http://localhost:9090/"
<h1>Hello Gee</h1>

curl -i "http://localhost:9090/login" -X POST -d 'username=geektutu&password=1234'
HTTP/1.1 200 OK
Content-Type: application/json
Date: Sun, 07 Jul 2024 06:16:11 GMT
Content-Length: 42

{"password":"1234","username":"geektutu"}
```