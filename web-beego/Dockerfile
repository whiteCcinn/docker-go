FROM golang:latest

MAINTAINER Caiwh <471113744@qq.com>

RUN go get github.com/astaxie/beego && go get github.com/beego/bee

EXPOSE 8080

# 使用bee命令开始对我们的应用程序进行实时重载。
CMD ["bee", "run"]
