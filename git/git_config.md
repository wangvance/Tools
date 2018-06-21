# git
git 的一般使用说明

---
## git 基本配置
### 设置 Git
* 安装git
yum or apt-get
* 设置用户信息
git config --global user.name "wang"
git config --global user.email "123@123.com"
执行完后会增加一个 .gitconfig 文件
### 添加 SSH Keys 到 GitHub 账号
* 创建 SSH key
$ ssh-keygen -t rsa -C "123@123.com"
默认生成到 /root/.ssh/id_rsa.pub
* 拷贝 SSH key
登录 GitHub ，"Setting" - "SSH keys" - "Add SSH key" - "Add key"
