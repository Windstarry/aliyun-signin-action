# aliyun-signin-action

利用 Github Actions 定时任务每天签到阿里云，领取礼包。

基于 https://github.com/ImYrS/aliyun-auto-signin 仓库，参考链接 https://hostloc.com/thread-1147588-1-6.html?d=1

获取REFRESH_TOKENS：https://alist.nn.ci/zh/guide/drivers/aliyundrive.html 按提示获取阿里云盘Token。

新建一个Personal access tokens (classic)：权限选择 repo。

在仓库的 Settings -> Secrets and Variables -> Actions 中点击 New repository secret 添加 Secrets和相应的值。
