#### 创建ssh密钥
1. 命令行输入 ssh-keygen -t rsa -b 4096 -C "youremail@gmail.com"
2. 然后一直按回车，最后创建成功
![](/img/ssh-new.png)
3. 显示id_rsa.pub的内容，并复制
![](/img/id_rsa.png)
4. 打开github --> setting --> SSH and GPG keys, 点击添加 New SSH key，将复制的公钥粘贴进来并保存，现在就可以使用git clone 命令了。
![](/img/ssh-key.png)