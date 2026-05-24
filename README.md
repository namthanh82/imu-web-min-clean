cat <<'EOF' | sudo tee /opt/retrack/run_server.sh >/dev/null
#!/usr/bin/env bash
set -euo pipefail

export RETRACK_RUNTIME=server
export PORT="${PORT:-5000}"

cd /opt/retrack
/usr/bin/python3 app.py
EOF
