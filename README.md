```
sudo apt-get update
wget https://mirrors.estointernet.in/apache//ant/binaries/apache-ant-1.10.9-bin.zip
sudo unzip apache-ant-1.10.9-bin.zip -d /usr/local
cd /usr/local/
sudo mv apache-ant-1.10.9/ apache-ant
sudo ln -s /usr/local/apache-ant/ /usr/local/ant
sudo apt install vim
vim /etc/profile.d/ant.sh
vi /etc/profile.d/ant.sh
export ANT_HOME=/usr/local/ant
export PATH=${ANT_HOME}/bin:${PATH}
esc
:wq
i 
esc
:wq
source /etc/profile
```

```
https://ant.apache.org/bindownload.cgi
ant is used to build files that are written in XML.
ant -buildfile ant.xml
ant
// for build.xml
```

