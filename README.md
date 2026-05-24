sudo cp /opt/retrack/retrack-backend.service /etc/systemd/system/retrack-backend.service
sudo systemctl daemon-reload
sudo systemctl enable retrack-backend.service
sudo systemctl start retrack-backend.service
sudo systemctl status retrack-backend.service
