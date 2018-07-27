## AWS CLI

AWSCLI 是由亚马逊提供的用于从命令行管理AWS服务的工具。

http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html

### 根据你的操作系统安装AWS CLI：

Mac
(http://docs.aws.amazon.com/cli/latest/userguide/cli-install-macos.html)

Windows
(https://s3.amazonaws.com/aws-cli/AWSCLI64.msi)

### CLI 概述

$ aws <command> <subcommand> [options and parameters]

### 配置 AWSCLI

为了将 AWSCLI 与新创建的AWS账户一起使用，你需要使用用户账户创建的访问密钥配置环境。

$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: ap-southeast-2
Default output format [None]: ENTER
