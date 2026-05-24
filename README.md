sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabled)
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24 16:38:58 BST; 29ms ago
 Invocation: 3afc394681e1459aa02531d7448cae25
    Process: 15239 ExecStart=/opt/retrack/run_server.sh (code=exited, status=1/FAILURE)
   Main PID: 15239 (code=exited, status=1/FAILURE)
        CPU: 7ms

May 24 16:38:58 komlab systemd[1]: retrack-backend.service: Main process exited, code=exited, status=1/FAILURE
May 24 16:38:58 komlab systemd[1]: retrack-backend.service: Failed with result 'exit-code'.
