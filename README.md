# use-tips

#### github 新仓库上传配置以及ssh连接

```bash
$ git init
$ git add . 
$ git remote 远程仓库
$ git push -u origin master

# ssh部分
# 本地生成ssh key：
ssh-keygen 
# 将ssh添加到ssh-agent
# 在后台启动 ssh-agent
$ eval $(ssh-agent -s)
> Agent pid 59566
#将 SSH 私钥添加到 ssh-agent。 如果您创建了不同名称的密钥，或者您要添加不同名称的现有密钥，请将命令中的 id_rsa 替换为您的私钥文件的名称。
$ ssh-add ~/.ssh/id_rsa  #id_rsa is your ssh key name

# 最后，将ssh key添加到GitHub账户

```

