# signal-server-setup-guide
## 安装环境

- Ubuntu 20.04
- Apache Maven 3.6.3
- Java 11.0.10
- Signal-Server 3.21

## 安装步骤

1. 环境准备

   ```
   sudo apt update
   sudo apt install git openjdk-11-jre-headless maven -y
   ```

2. 下载文件

   ```
   git clone https://github.com/hejinlong/signal-server-setup-guide.git
   ```

3. 解压文件

   ```
   cd signal-server-setup-guide
   unzip Signal-Server-3.21.zip
   cd Signal-Server-3.21
   ```

4. 构建服务器

   ```
   mvn clean install -DskipTests
   ```

   
