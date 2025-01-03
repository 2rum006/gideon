pkg update

pkg upgrade -y

pkg install git

pkg install python-pip

git clone https://github.com/2rum006/gideon.git

cd gideon

git pull

python3 -m pip install requests

pkg i python-numpy

pip install rich --upgrade

pip install -r requirements.txt

pip3 install pystyle

python3 main.py