namthanh5555@komlab:/opt/retrack $ sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service
● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabled)
     Active: active (running) since Sun 2026-05-24 16:43:47 BST; 22ms ago
 Invocation: 1381edb67b5d4edbabfcd7f35cf9a042
   Main PID: 15451 ((erver.sh))
      Tasks: 1 (limit: 9571)
        CPU: 5ms
     CGroup: /system.slice/retrack-backend.service
             └─15451 "(erver.sh)"

May 24 16:43:47 komlab systemd[1]: Started retrack-backend.service - ReTrack Flask Backend.
