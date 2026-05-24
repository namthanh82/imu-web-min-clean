sudo systemctl stop retrack-backend.service
sudo systemctl disable retrack-backend.service
sudo rm -f /etc/systemd/system/retrack-backend.service
sudo systemctl daemon-reload
