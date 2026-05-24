#!/usr/bin/env bash
set -euo pipefail

export RETRACK_RUNTIME=server
export PORT="${PORT:-5000}"

cd /home/namthanh5555/Downloads/imu-web-min-clean
source .venv/bin/activate
python3 app.py
