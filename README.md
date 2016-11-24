# Vagrant Docker
基于 Vagrant 的 Docker 环境.

## 用法

### 1. 安装 Vagrant
已安装的可以略过。

参见 <https://www.vagrantup.com/docs/installation/>

### 2. 下载代码

```bash
git clone https://github.com/iPaya/vagrant-docker.git
```

### 3. 运行
```bash
cd vagrant-docker && vagrant up
```

### 4. 打包并添加到 box
```bash
vagrant package && vagrant box add aPaya/docker package.box
```