# Typecho_On_Vercel
Typecho run on vercel used MySQL SSL Connection

## 安装：
①Fork 本仓库

②修改```config.inc.php```里面的数据库信息，不用```ssl/tls```连接mysql```tls```直接留空

③上传部署到vercel，不会的话自行google

④访问 ```https://域名/install.php``` 进行安装

⑤完成

PS:由于Vercel是Serverless的方案，所以屏蔽了安装检测上传权限的语句

基于```Typecho 1.2.0```修改，动了两个地方，一个是跳过安装时检测```upload```权限，一个是```pdo_mysql```适配```ssl/tls```连接，其他地方都没动，留一个repository方便以后自己查看
