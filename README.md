amthanh5555@komlab:~/Downloads $ cd /opt/retrack
namthanh5555@komlab:/opt/retrack $ sudo systemctl start retrack-backend.servicez
Failed to start retrack-backend.servicez.service: Unit retrack-backend.servicez.service not found.
namthanh5555@komlab:/opt/retrack $ sudo systemctl start retrack-backend.service
namthanh5555@komlab:/opt/retrack $ sudo systemctl status retrack-backend.service
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; pres>
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24>
 Invocation: 0a6e142a06b04fd58bda9ad377c78a54
    Process: 14280 ExecStart=/opt/retrack/run_server.sh (code=exited, status=1/>
   Main PID: 14280 (code=exited, status=1/FAILURE)
        CPU: 9ms
lines 1-7/7 (END)...skipping...
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabled)
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24 16:23:19 BST; 1s ago
 Invocation: 0a6e142a06b04fd58bda9ad377c78a54
    Process: 14280 ExecStart=/opt/retrack/run_server.sh (code=exited, status=1/FAILURE)
   Main PID: 14280 (code=exited, status=1/FAILURE)
        CPU: 9ms
~
