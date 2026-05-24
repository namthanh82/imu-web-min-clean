amthanh5555@komlab:~/Downloads $ journalctl -u retrack-backend.service -n 50 --no-pager
May 24 13:03:13 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:13 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:16 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 540.
May 24 13:03:16 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:16 komlab run_server.sh[4419]: env: ‘bash\r’: No such file or directory
May 24 13:03:16 komlab run_server.sh[4419]: env: use -[v]S to pass options in shebang lines
May 24 13:03:16 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:16 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:19 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 541.
May 24 13:03:19 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:19 komlab run_server.sh[4421]: env: ‘bash\r’: No such file or directory
May 24 13:03:19 komlab run_server.sh[4421]: env: use -[v]S to pass options in shebang lines
May 24 13:03:19 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:19 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:22 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 542.
May 24 13:03:22 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:22 komlab run_server.sh[4423]: env: ‘bash\r’: No such file or directory
May 24 13:03:22 komlab run_server.sh[4423]: env: use -[v]S to pass options in shebang lines
May 24 13:03:22 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:22 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:26 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 543.
May 24 13:03:26 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:26 komlab run_server.sh[4425]: env: ‘bash\r’: No such file or directory
May 24 13:03:26 komlab run_server.sh[4425]: env: use -[v]S to pass options in shebang lines
May 24 13:03:26 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:26 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:29 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 544.
May 24 13:03:29 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:29 komlab run_server.sh[4427]: env: ‘bash\r’: No such file or directory
May 24 13:03:29 komlab run_server.sh[4427]: env: use -[v]S to pass options in shebang lines
May 24 13:03:29 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:29 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:32 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 545.
May 24 13:03:32 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:32 komlab run_server.sh[4429]: env: ‘bash\r’: No such file or directory
May 24 13:03:32 komlab run_server.sh[4429]: env: use -[v]S to pass options in shebang lines
May 24 13:03:32 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:32 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:35 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 546.
May 24 13:03:35 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:35 komlab run_server.sh[4431]: env: ‘bash\r’: No such file or directory
May 24 13:03:35 komlab run_server.sh[4431]: env: use -[v]S to pass options in shebang lines
May 24 13:03:35 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:35 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
May 24 13:03:39 komlab systemd[1]: retrack-backend.service: Scheduled restart job, restart counter is at 547.
May 24 13:03:39 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
May 24 13:03:39 komlab run_server.sh[4433]: env: ‘bash\r’: No such file or directory
May 24 13:03:39 komlab run_server.sh[4433]: env: use -[v]S to pass options in shebang lines
May 24 13:03:39 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=127/n/a
May 24 13:03:39 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
python3 app.pynamthanh5555@komlab:~/Downloads $ ^C
namthanh5555@komlab:~/Downloads $ cat /opt/retrack/run_server.sh
#!/usr/bin/env bash
set -euo pipefail

export RETRACK_RUNTIME=server
export PORT="${PORT:-5000}"

