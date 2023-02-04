wget https://disk.yandex.ru/d/gtT1VdX5hvnXwg
cp bionic-server-cloudimg-amd64-vagrant.box /data/bionic-server-cloudimg-amd64-vagrant.box
vagrant box add ubuntu/bionic64 /data/bionic-server-cloudimg-amd64-vagrant.box
vagrant up
