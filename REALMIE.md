pkg update && pkg upgrade
pkg install python-pip
pkg install git
git clone https://github.com/Han-ID/Kang-Nyepam
cd Kang-Nyepam
pip install -r requirements.txt
git pull
python run.py
