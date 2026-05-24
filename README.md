namthanh5555@komlab:~/Downloads $ sudo systemctl daemon-reload
sudo systemctl enable retrack-backend.service
sudo systemctl start retrack-backend.service
sudo systemctl status retrack-backend.service
Created symlink '/etc/systemd/system/multi-user.target.wants/retrack-backend.service' → '/etc/systemd/system/retrack-backend.service'.
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; pres>
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24>
 Invocation: 885733e33c24401aaeefa3c1be08eef1
    Process: 3292 ExecStart=/opt/retrack/run_server.sh (code=exited, status=127)
   Main PID: 3292 (code=exited, status=127)
        CPU: 6ms
lines 1-7/7 (END)























● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; pres>
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24>
 Invocation: 885733e33c24401aaeefa3c1be08eef1
    Process: 3292 ExecStart=/opt/retrack/run_server.sh (code=exited, status=127)
   Main PID: 3292 (code=exited, status=127)
        CPU: 6ms
