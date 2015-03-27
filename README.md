Special Thanks DotInstall !
Setup local development environment.  Installs Apache, PHP, MySQL, Ruby and Node.js.  See main.yml for more details.

```
mkdir mycentos && cd mycentos
vagrant init chef/centos-7.0
vi Vagrantfile # IP編集
vagrant up
vagrant ssh
sudo yum -y install git
git clone https://github.com/terurururu/centos70.git
cd centos70
./run.sh
```

If you need to update the script, please follow the instruction below.

```
cd
git clone https://github.com/terurururu/centos70.git
cd centos70
./run.sh
```


