namthanh5555@komlab:~/Downloads $ sudo systemctl daemon-reload
sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabled)
     Active: active (running) since Sun 2026-05-24 13:46:36 BST; 31ms ago
 Invocation: 7bba9bc9b1954d54b2d43a84969ee9b6
   Main PID: 7602 (bash)
      Tasks: 2 (limit: 9571)
        CPU: 12ms
     CGroup: /system.slice/retrack-backend.service
             ├─7602 bash /opt/retrack/run_server.sh
             └─7609 ./ReTrack

May 24 13:46:36 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
namthanh5555@komlab:~/Downloads $ chromium --kiosk http://127.0.0.1:5000/login
