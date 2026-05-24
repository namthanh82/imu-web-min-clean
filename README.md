sudo chmod +x /opt/retrack/run_server.sh
sudo systemctl daemon-reload
sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service
