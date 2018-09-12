# use git
  Most commonly used git tips and tricks. http://git.io/git-tips
# fix-arduino-linux
  http://arduino-er.blogspot.com/2014/08/arduino-ide-error-avrdude-seropen-cant.html
# scroll-lock:
  https://unix.stackexchange.com/questions/164245/why-is-the-scroll-lock-key-disabled-in-cinnamon-linux-xorg
# unable-to-lock:
 https://askubuntu.com/questions/15433/unable-to-lock-the-administration-directory-var-lib-dpkg-is-another-process
# font
  http://taimienphi.vn/download-font-times-new-roman-35803/taive
# setup VMware
  https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-vmware-workstation-pro-14-on-ubuntu-18-04-17-10-ubuntu-16-04.html
# unkikey: 
  https://nguyenhuuhoang.com/huong-dan-cai-bo-go-tieng-viet-tren-ubuntu-16-04-lts-ibus-unikey/
# git: 
  http://phamquan.com/tutorials/git-co-ban/cai-dat-git-tren-ubuntu.html
# setupapp: 
  https://kungfuphp.com/node-js/cai-dat-node-js-tren-ubuntu-14-04.html
# nodejs: 
  http://webfaver.com/build-stack/cach-bien-dich-va-cai-dat-nodejs-tren-ubuntu-14-0414-1015-04.html
# visual: 
  http://echip.pro/4rum/threads/lap-trinh-c-bang-visual-studio-code-tren-ubuntu.145.html
# chrome: 
  http://tuong.me/huong-dan-cai-dat-google-chrome-tren-ubuntu-16-04-16-10/
# fix Could not open /dev/vmmon VMware
  https://stackoverflow.com/questions/49205162/install-vmware-could-not-open-dev-vmmon-no-such-file-or-directory-please-ma
# setup-off
  sudo dpkg -i <tenfile>.deb
  
  sudo apt-get install -f
  
  # setup apache 2
  https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-16-04
  
  # xoa git
  https://askubuntu.com/questions/824696/is-it-fine-to-remove-the-opt-gitlab-directory-manually-after-removing-the-gitl
  
  # install php mysql
  https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04
  
  # install phpmyadmin
  https://www.hostingadvice.com/how-to/install-phpmyadmin-on-ubuntu/
  
  # tao sub domain ubuntu
  https://www.trungnotes.com/lap-trinh/124-them-domain-hoac-subdomain-tren-vps-ubuntu-debian-hay-centos
  
  # cách cài dat https
  https://vinadata.vn/bao-mat-apache-lets-encrypt-ubuntu-16-04/
  
  # cách chay node port 80
    https://seeq12.atlassian.net/wiki/spaces/KB/pages/116188360/Apache+Reverse+Proxy+for+HTTPS+on+Ubuntu
    https://www.digitalocean.com/community/tutorials/how-to-use-apache-as-a-reverse-proxy-with-mod_proxy-on-ubuntu-16-04
 # cách cái gitea
  https://gist.github.com/appleboy/36313a525fbef673f8aefadb9c0f8247
  
 #run all permistion
  exp: sudo npm install --save node-sass-chokidar --unsafe-perm=true --allow-root
  
 # enable auth mongodb
  https://stackoverflow.com/questions/4881208/how-to-secure-mongodb-with-username-and-password
 # tạo mail free với yarn dex
 https://canhme.com/kinh-nghiem/tao-email-ten-mien-rieng-voi-yandex/
 
 # cấu hình apache chay 1 file index.html
      DirectoryIndex index.html
      #RewriteRule ^*$  http://www.addomain.com/index.html [R=301,NC,L]
      AliasMatch ^(?:(?!\.).)*$ /var/www/project/fintechvn/insurFrontEnd/build/index.html
      
 # fix authen mogo in loopback
 ```json
 "mongodb": {
    "host": "myHost",
    "port": 27017,
    "database": "myDB",
    "password": "myPass",
    "name": "mongodb",
    "user": "myUser",
    "connector": "mongodb",
    "authSource": "admin",
    "useNewUrlParser": true
  }
  ```
  
  # fix rockmongo connect mongo authen
    cd rockmongo-php7
    cd app/models
    sudo vi MDb.php // line 35
    // remove true in function 
        $colls = $db->listCollections();

