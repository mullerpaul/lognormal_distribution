# produce data with a lognormal distribution using Python


# new repo
git init lognormal_dist
cd lognormal_dist/

pip --version
# pip not installed!

sudo apt update
sudo apt install python3-pip
pip3 --version
pip3 install pandas
pip3 install notebook

jupyter notebook
# jupyter not installed!

sudo apt install jupyter-core

# now add python script location to path
export PATH="$HOME/.local/bin:$PATH" >> .bashrc
source .bashrc

# now inistall matplotlib for histogram graphs
pip3 install matplotlib

