运行失败请执行

#Debian、Ubuntu

apt-get install -y wget && apt-get install -y ca-certificates

#CentOS

yum install -y wget && yum install -y ca-certificates

指定源

bash repoupdate.sh cn

bash repoupdate.sh 163

bash repoupdate.sh aliyun

bash repoupdate.sh aws

如果配置的文件不满意，一键还原

bash repoupdate.sh restore
