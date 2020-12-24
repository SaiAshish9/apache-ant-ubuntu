```
sudo apt-get update
wget https://mirrors.estointernet.in/apache//ant/binaries/apache-ant-1.10.9-bin.zip
sudo unzip apache-ant-1.10.9-bin.zip -d /usr/local
cd /usr/local/
sudo mv apache-ant-1.10.9/ apache-ant
sudo ln -s /usr/local/apache-ant/ /usr/local/apache-ant/
vim /etc/profile.d/ant.sh
```

```
https://ant.apache.org/bindownload.cgi
ant is used to build files that are written in XML.
ant -buildfile ant.xml
ant
// for build.xml
```

