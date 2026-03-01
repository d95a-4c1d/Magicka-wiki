## 编辑容器教程
容器修改后，网页端不会立即产生修改，需要重启容器
### 停止容器
输入
```bash
docker ps
```
获取对应的容器名称，然后使用
```bash
docker stop [对应名称]
```
关闭容器
### 重启容器
使用
```bash
docker run --rm -it -p 80:80 -v ${PWD}:/docs --user $(id -u):$(id -g) squidfunk/mkdocs-material serve --dev-addr=0.0.0.0:80
```# Magicka-wiki
