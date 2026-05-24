git clone https://github.com/namthanh82/imu-web-min-clean.git
cd imu-web-min-clean
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 app.py
namthanh5555@komlab:~/Downloads $ sudo systemctl start retrack-backend.service
Failed to start retrack-backend.service: Unit retrack-backend.service not found
