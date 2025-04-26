# CentOS7-pptp-host1plus

## Run Change source
```
mkdir /etc/yum.repos.d/bak
mv -f /etc/yum.repos.d/*.repo /etc/yum.repos.d/bak/
curl http://mirrors.aliyun.com/repo/Centos-7.repo -o /etc/yum.repos.d/Centos-7.repo
sudo yum clean all
sudo yum makecache
```


## Run
```
curl -O https://raw.githubusercontent.com/jiu-chuan/CentOS7-pptp-host1plus/refs/heads/main/CentOS7-pptp-host1plus.sh
chmod +x ./CentOS7-pptp-host1plus.sh
./CentOS7-pptp-host1plus.sh -u your_username -p your_password
```
