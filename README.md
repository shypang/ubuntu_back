# ubuntu_back


#backup 
dpkg --get-selections | grep -v deinstall > 설치내역.txt

#restore
sudo dpkg --set-selections < 설치내역.txt


