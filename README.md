# test
a.配置用户名：git config --global user.name (git上注册的用户名) eg: git config --global user.name "zhangsan"
b.配置邮箱：git config --global user.email (git上的邮箱) eg: git config --global user.email "zhangsan@qq.com"
c.查看配置后的用户名及邮箱： git config user.name    git config user.email
d.生成公私钥: ssh-keygen -t rsa -C"git上注册的邮箱" eg:ssh-keygen -t rsa -C"zhangsan@qq.com"
e.输入保存公私钥的文件：
f.输入密码，再次输入密码
h.登录github，设置sshkey。点击settings->New SSH Key,填上任意title,将生成的公钥复制到key的文本框，点击ADD。
i.创建repository,保存https地址（在clone or download中）
