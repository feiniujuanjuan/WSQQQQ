## 检查本地主机是否已经存在ssh key

    cd ~/.ssh
    ls
    //看是否存在 id_rsa 和 id_rsa.pub文件，如果存在，说明已经有SSH Key

## 生成SSH秘钥

    ssh-keygen -t rsa -C "xxx@xxx.com"
    //执行后一直回车即可

## 获取ssh key公钥内容

    cd ~/.ssh
    cat id_rsa.pub

### 撤销本地错误合并还没有推送到远端的操作

    git reset --hard HEAD^

