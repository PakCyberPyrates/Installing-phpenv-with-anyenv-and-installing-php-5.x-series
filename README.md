* It takes quite a long time to finish all the time.


fix  the issue by installing extra libraries, the whole list

sudo apt-get install -y autoconf g++ make openssl libssl-dev libcurl4-openssl-dev

sudo apt-get install -y libcurl4-openssl-dev pkg-config

sudo apt-get install -y libsasl2-dev



$ cat /etc/lsb-release

Installation of Git (if not included)

sudo add-apt-repository -y ppa:git-core/ppa

sudo apt-get update && sudo apt-get install git -y

git --version

curl -L http://git.io/phpenv-installer | bash

$ echo 'export PATH="$HOME/.phpenv/bin:$PATH"' >> ~/.bashrc

$ echo 'eval "$(phpenv init -)"' >> ~/.bashrc

$ exec $SHELL -l

sudo apt-get install -y libssl-dev libmcrypt-dev libreadline-dev libxslt1-dev libxml2-dev libbz2-dev libcurl4-openssl-dev libpng-dev libjpeg-dev libmcrypt-dev libsqlite-dev libtidy-dev libltdl-dev make autoconf automake re2c lemon

$ wget http://launchpadlibrarian.net/121520545/libbison-dev_2.6.2.dfsg-1_amd64.deb

$ wget https://launchpad.net/ubuntu/+source/bison/1:2.6.2.dfsg-1/+build/3935803/+files/bison_2.6.2.dfsg-1_amd64.deb

$ sudo dpkg -i libbison-dev_2.6.2.dfsg-1_amd64.deb

$ sudo dpkg -i bison_2.6.2.dfsg-1_amd64.deb

phpenv install -l

phpenv install 5.4.45 && phpenv install 5.5.38 && phpenv install 5.6.40 && phpenv install 7.1.30 && phpenv install 7.2.19 && phpenv install 7.3.6 && phpenv install 7.4snapshot

phpenv global 7.0.11

php --version


phpenv global 5.3.29

phpenv install -l
