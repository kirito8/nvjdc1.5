# nvjdcdocker
1.2版本及以后快速升级：

cd /volume1/docker/nvjdc
sudo docker stop nvjdc
git pull
sudo docker start nvjdc

#拉源码
git clone https://ghproxy.com/https://github.com/NolanHzy/nvjdcdocker.git /root/nolanjdc

#拉镜像
sudo docker pull nolanhzy/nvjdc:latest
