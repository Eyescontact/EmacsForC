1、安装  GNU Global    
sudo apt-get build-dep global<br />
sudo apt-get install libncurses5-dev libncursesw5-dev
<br />
下载 global：http://www.gnu.org/software/global/download.html 解压进入
<br/>./configure --with-sqlite3
<br/>make -j4
<br/>make check
<br/>sudo make install
<br/>sudo make installcheck<br/>
完成可检查是否成功 global --version
