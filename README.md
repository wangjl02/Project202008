# Project202008
外包项目工程文件
#添加SSH公钥的步骤
ssh-keygen -t rsa -C "1143428977@qq.com"
输入passphrase
gvim /root/.ssh/id_rsa.pub，将内部的信息复制
添加到github的公钥中
测试是否成功添加公钥
ssh -T git@github.com
