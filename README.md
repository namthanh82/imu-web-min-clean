May 24 13:39:40 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:39:40 komlab run_server.sh[7042]: /usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
May 24 13:39:40 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=2/INVALIDARGUMENT
May 24 13:39:40 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:39:43 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 103.
May 24 13:39:43 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:39:43 komlab run_server.sh[7045]: /usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
May 24 13:39:43 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=2/INVALIDARGUMENT
May 24 13:39:43 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:39:47 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 104.
May 24 13:39:47 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:39:47 komlab run_server.sh[7048]: /usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
May 24 13:39:47 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=2/INVALIDARGUMENT
May 24 13:39:47 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:39:50 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 105.
May 24 13:39:50 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:39:50 komlab run_server.sh[7051]: /usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
May 24 13:39:50 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=2/INVALIDARGUMENT
May 24 13:39:50 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:39:53 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 106.
May 24 13:39:53 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:39:53 komlab run_server.sh[7054]: /usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
May 24 13:39:53 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=2/INVALIDARGUMENT
May 24 13:39:53 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:39:56 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 107.
namthanh5555@komlab:~/Downloads $ cat /opt/retrack/run_server.sh
#!/usr/bin/env bash
set -euo pipefail

export RETRACK_RUNTIME=server
export PORT="${PORT:-5000}"

cd /opt/retrack
/usr/bin/python3 app.py
namthanh5555@komlab:~/Downloads $ cd /opt/retrack
namthanh5555@komlab:/opt/retrack $ /opt/retrack/run_server.sh
/usr/bin/python3: can't open file '/opt/retrack/app.py': [Errno 2] No such file or directory
