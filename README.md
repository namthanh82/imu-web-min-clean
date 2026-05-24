sudo chmod +x /opt/retrack/run_server.sh
sudo systemctl restart retrack-backend.service
sudo systemctl status retrack-backend.service


● retrack-backend.service - ReTrack Flask Backend
     Loaded: loaded (/etc/systemd/system/retrack-backend.service; enabled; preset: enabl>
     Active: activating (auto-restart) (Result: exit-code) since Sun 2026-05-24 14:05:17>
 Invocation: 6d0b03d39efc4ca0bd5dcfde084a7d32
    Process: 8725 ExecStart=/opt/retrack/run_server.sh (code=exited, status=1/FAILURE)
   Main PID: 8725 (code=exited, status=1/FAILURE)
        CPU: 10ms
