namthanh5555@komlab:~/Downloads $ sudo systemctl  status retrack-backend.service
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabled)
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24 13:34:44 BST; 2s ago
 Invocation: cbfb91044baa47beb89058b3acddeced
    Process: 6662 ExecStart=/opt/retrack/run_server.sh (code=exited, status=2)
   Main PID: 6662 (code=exited, status=2)
        CPU: 31ms
        
namthanh5555@komlab:~/Downloads $ chromium --kiosk http://127.0.0.1:5000/login
Opening in existing browser session.
