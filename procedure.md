1、安装  GNU Global    
sudo apt-get build-dep global<br />
sudo apt-get install libncurses5-dev libncursesw5-dev
<br />
下载 global：http://www.gnu.org/software/global/download.html 解压进入
./configure --with-sqlite3
make -j4
make check
sudo make install
sudo make installcheck
