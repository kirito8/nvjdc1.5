# nvjdcdocker
1.2版本及以后快速升级：

cd /root/nolanjdc
docker stop nolanjdc
git pull
docker start nolanjdc
docker logs -f nolanjdc 

#拉源码
git clone https://github.com/NolanHzy/nvjdcdocker.git /root/nolanjdc

#拉镜像
sudo docker pull nolanhzy/nvjdc:latest
