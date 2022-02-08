# 获取自己当前公网 IP 的镜像

```sh
# 获取自己的公网 IP
$ docker run myip
当前 IP：xxx.xxx.xx.xxx  来自于：中国 北京 北京  联通
# 想加上 -i 参数, 报错了
$ docker run myip -i
docker: Error response from daemon: OCI runtime create failed: container_linux.go:346: starting container process caused "exec: \"-i\": executable file not found in $PATH": unknown.
```