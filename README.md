# MaiMbotwebwithlog
一个简单的web用于展示麦麦信息和实时日志，需要手动修改json配置文件

# 需要的相关软件

1. nginx 用于反向代理网页
2. frp 配合阿里云服务器实现内网穿透
3. supervisor 使用 supervisor 配合源码部署麦麦，然后配合 nginx 反向代理服务，公开日志界面
