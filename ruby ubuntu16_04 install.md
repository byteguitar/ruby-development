ubuntu16-04 install ruby rails
==================
# ruby install
       sudo apt-get install ruby-full
       sudo apt-get install rails
       sudo apt-get install libsqlite3-dev   * 否则会出现bundle install 无法安装sqllite3
       
# bundle install 出现问题
       进入生成的站点目录 解决依赖问题bundle lock --add-platform x86-mingw32 x86-mswin32 x64-mingw32 java

# rails server 出现Could not find a JavaScript runtime的问题       
       sudo apt-get install python-software-properties
       sudo add-apt-repository ppa:chris-lea/node.js
       sudo apt-get update
       sudo apt-get install nodejs
       安装一个nodejs就ok了
       如果只有nodejs 没有node命令
       sudo ln -s /usr/bin/nodejs /usr/bin/node
#  安装 sublimetext 
       sudo add-apt-repository ppa:webupd8team/sublime-text-3
       sudo apt-get update
       sudo apt-get install sublime-text-installer
#  install mysql2
       使用mysql2前
       sudo apt-get install libmysqlclient-dev 
