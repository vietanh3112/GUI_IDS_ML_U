cd GuiUbuntu-20260405T173006Z-1-001/GuiUbuntu  
sudo apt update  
sudo apt install -y python3-venv python3-full  
python3 -m venv .venv  
source .venv/bin/activate  
python -m pip install --upgrade pip  
pip install -r requirements.txt  
source .venv/bin/activate  
python3 anm_monitor.py  
