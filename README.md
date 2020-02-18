## workshare (for users) ##

- `yum install rpcbind`
- `/etc/init.d/rpcbind start`
- `mkdir -p 想要掛的目錄`
- `mount -t nfs 140.122.249.145:/workshare 想要掛的目錄`
- `df` 檢查是否成功
