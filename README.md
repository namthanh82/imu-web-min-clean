cat <<'EOF' | sudo tee /opt/retrack/run_server.sh >/dev/null
#!/usr/bin/env bash
set -euo pipefail

export RETRACK_RUNTIME=server
export PORT="${PORT:-5000}"

cd /opt/retrack
./ReTrack
EOF

sudo chmod +x /opt/retrack/run_server.sh
sudo systemctl daemon-reload
sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service
