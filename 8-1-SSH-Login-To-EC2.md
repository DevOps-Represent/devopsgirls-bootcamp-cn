## SSH登录到您的EC2实例

### 1) 找到您的EC2实例的公网IP
在AWS中单击EC2

转到正在运行的实例

找到并选择您的EC2实例

复制EC2实例的IPv4公网IP地址

### 2) 将.pem秘钥文件的属性更改为“只读”
打开你的终端

转到下载的.pem密钥文件的目录，将文件属性更改为只读

在命令行中运行命令（假设您已将其保存在Downloads目录中）:

`$chmod 400 ~/Downloads/keyname.pem`

例如
$chmod 400 ~/Downloads/leorentanyag.pem 
 
### 3) 使用你的pem秘钥通过SSH登录你的实例

`ssh -i ~/Downloads/<keyname.pem> ec2-user@<公网IPv4地址>`

例如:
ssh -i ~/Downloads/leorentanyag.pem ec2-user@13.55.214.58
