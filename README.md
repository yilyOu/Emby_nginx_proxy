# Nginx Emby  一键反代指南

### 此页脚本支持Emby前后端推流服务器不同域名后缀下的反向代理

### [单域名反向代理]()

# 下载运行
1. 下载脚本
```bash
wget https://raw.githubusercontent.com/dogliu666/Emby_ReverseProxy/refs/heads/beta/Proxy_Louis.sh
```
> 注意：可能存在重复下载文件，需要手动删除文件

2. 运行脚本
```
bash Proxy_Louis.sh
```

# 若需要修改反代地址，参考以下步骤
```bash
nano /etc/nginx/proxy_louis.conf
```

此时修改内部的`EMBY_URL` `STREAM_COUNT`等配置即可
