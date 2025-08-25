cd /usr/src
rm -fv csf.tgz
wget https://github.com/gitcfro1/csf/blob/main/csf.tgz
tar -xzf csf.tgz
cd csf
sh install.sh
cd /home/
wget https://github.com/gitcfro1/csf/blob/main/cmq.tgz
tar -xzf cmq.tgz
cd cmq/
sh install.sh
cd /usr/src
rm -fv /usr/src/cmm.tgz
wget https://github.com/gitcfro1/csf/blob/main/cmm.tgz
tar -xzf cmm.tgz
cd cmm
sh install.sh
rm -Rfv /usr/src/cmm*
cd /usr/src
rm -fv /usr/src/cmc.tgz
wget https://github.com/gitcfro1/csf/blob/main/cmc.tgz
tar -xzf cmc.tgz
cd cmc
sh install.sh
rm -Rfv /usr/src/cmc*
