# docs.loraserver.io

本repo包含LoRa Server项目文档。

## Build

需要[Hugo](http://gohugo.io/)把MarkDown文件转为HTML文件。

### 安装 Hugo

从Hugo网站下载二进制文件，或直接从源码编译安装：

```bash
go get -v github.com/spf13/hugo
```

### 启动 Hugo

启动Hugo，从本 repo 根目录执行以下命令即可：

```bash
hugo server -w
```