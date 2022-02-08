# 获取自己当前公网 IP 的镜像

```sh
# 获取自己的公网 IP
$ docker run myip
当前 IP：xxx.xxx.xx.xxx  来自于：中国 北京 北京  联通
# 想加上 -i 参数, 能正确返回
$ docker run myip -i
HTTP/1.1 200 OK
Date: Tue, 08 Feb 2022 03:04:23 GMT
Content-Type: text/plain; charset=utf-8
Content-Length: 69
Connection: keep-alive
X-Via-JSL: fdc330b,-
Set-Cookie: __jsluid_h=b9173bbc30980351ef44736905d4c556; max-age=31536000; path=/; HttpOnly
X-Cache: bypass

当前 IP：xxx.xxx.xx.xxx  来自于：中国 北京 北京  联通
```