[七天手写web框架参考](https://geektutu.com/post/gee-day1.html)
###  测试示例
% curl  -i  localhost:9090/
HTTP/1.1 200 OK
Date: Fri, 05 Jul 2024 03:16:15 GMT
Content-Length: 15
Content-Type: text/plain; charset=utf-8
URL.Path = "/"

% curl  -i  localhost:9090/hello
HTTP/1.1 200 OK
Date: Fri, 05 Jul 2024 03:17:05 GMT
Content-Length: 66
Content-Type: text/plain; charset=utf-8
Header["User-Agent"] = ["curl/7.79.1"]
Header["Accept"] = ["*/*"]


% curl  -i  localhost:9090/zhangxh
HTTP/1.1 404 Not Found
Date: Fri, 05 Jul 2024 03:17:30 GMT
Content-Length: 24
Content-Type: text/plain; charset=utf-8
404 NOT FOUND: /zhangxh

