# 安装 Flutter SDK

## 方法 1: 使用 Snap (推荐，Ubuntu/Debian)

```bash
sudo snap install flutter --classic
```

## 方法 2: 手动安装

```bash
# 1. 下载 Flutter
cd /opt
sudo wget https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.24.0-stable.tar.xz
sudo tar xf flutter_linux_3.24.0-stable.tar.xz
sudo chown -R $USER:$USER flutter

# 2. 添加到 PATH
echo 'export PATH="$PATH:/opt/flutter/bin"' >> ~/.bashrc
source ~/.bashrc

# 3. 验证安装
flutter --version
```

## 安装后

```bash
cd /home/admin/openclaw/workspace/tv-live-app
./build.sh
```
