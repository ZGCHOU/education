# education
将`GOPATH`设置为`/root/go`,拉取项目：
```
cd $GOPATH/src && git clone https://github.com/sxguan/education.git
```
添加依赖：
```
cd education && go mod tidy
```
运行项目：
```
./clean_docker.sh
```
在`127.0.0.1:9000`进行访问
