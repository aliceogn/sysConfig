sudo apt update -y && sudo apt upgrade -y
sudo apt install git 
sudo apt install default-jdk
git clone https://github.com/aliceogn/introprg.git
bash .introprg/configura_introprg.sh 
source ~/.bashrc 
bash .introprg/install_junit.sh
source ~/.bashrc 
sudo apt install sqlite3
bash .introprg/install_sqlite_jdbc.sh
(if causes problems, then 
source ~/.bashrc
bash .introprg/install_sqlite_jdbc.sh)
git config --global user.email "aliceogn@gmail.com"
