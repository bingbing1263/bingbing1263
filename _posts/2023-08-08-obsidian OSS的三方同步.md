阿里的OSS， 一年9块钱40G的空间，上传不收流量费，下载要收流量费。
1. 买好空间。
2. 创建Bucket
3. 跨域设置，安全/跨域设置中，来源：
> app://obsidian.md 
> capacitor://localhost
> http://localhost
4. Methods全部勾选，Header中填入 \*， 点击完成
5. 授权设置。为这个笔记单独建一下子账号来管理资源，创建新用户，获得Accesskey id和accesskey secret. 记住这两个，关了页面无法再获取了。OPEN API 调用访问。另一个不需要。
6. 授权给这个账户  完全控制。
7. 然后就是安装Remotely save，并进行设置。
