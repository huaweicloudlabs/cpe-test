# docker-test
 for docker test

## 代码编译构建
git clone代码后，执行如下操作 mvn install -f pom.xml -s settings.xml

## 打docker镜像
在product-service的target目录下，会生成Dockerfile， copy到代码目录，然后执行  docker build -t product-service:version .
