# CentOS7-pptp-host1plus

## Run Change source
```
cd /etc/yum.repos.d/
mkdir bak
mv *.repo bak/
curl -O  http://mirrors.aliyun.com/repo/Centos-7.repo
sudo yum clean all
sudo yum makecache
```


## Run
```
cd /root/
curl -O https://raw.githubusercontent.com/jiu-chuan/CentOS7-pptp-host1plus/refs/heads/main/CentOS7-pptp-host1plus.sh
chmod +x ./CentOS7-pptp-host1plus.sh
./CentOS7-pptp-host1plus.sh -u your_username -p your_password
```
