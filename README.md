# Download-GitHub-Release
> 使用该脚本批量下载GitHub Release中最新版本所有文件

## 预先准备

### Centos
```
yum install ca-certificates wget -y && update-ca-trust force-enable
```
### Debian｜Ubuntu
```
apt-get install ca-certificates wget -y && update-ca-certificates
```

---

## 用法

```
chmod a+x [download-github-release.sh](http://download-github-release.sh/)
```

### 默认下载最新release

```
./download-github-release.sh latest v2fly v2ray-core
```

### 下载指定release

```
./download-github-release.sh custom v2fly v2ray-core v1.6.0-rc5
```
