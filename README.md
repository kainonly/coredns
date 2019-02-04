# coredns

拉取 k8s.gcr.io 镜像

```shell
docker push kainonly/coredns:1.2.6
// or
docker pull ccr.ccs.tencentyun.com/kainonly/coredns:1.2.6
```

重命名镜像

```shell
docker tag kainonly/coredns:1.2.6 k8s.gcr.io/coredns:1.2.6
// or
docker tag ccr.ccs.tencentyun.com/kainonly/coredns:1.2.6 k8s.gcr.io/coredns:1.2.6
```

删除镜像

```shell
docker rmi kainonly/coredns:1.2.6
// or
docker rmi ccr.ccs.tencentyun.com/kainonly/coredns:1.2.6
```