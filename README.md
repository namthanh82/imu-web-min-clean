.venv) namthanh5555@komlab:~/Downloads/imu-web-min-clean-main $ python3 app.py
Server listening on port 8080.
 * Serving Flask app 'webgiaodien'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:8080
 * Running on http://192.168.100.69:8080
Press CTRL+C to quit
Exception in thread Thread-1:
Traceback (most recent call last):
  File "/usr/lib/python3.13/threading.py", line 1043, in _bootstrap_inner
    self.run()
    ~~~~~~~~^^
  File "/usr/lib/python3.13/threading.py", line 1344, in run
    self.function(*self.args, **self.kwargs)
    ~~~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/namthanh5555/Downloads/imu-web-min-clean-main/app.py", line 328, in <lambda>
    Timer(1.5, lambda: webbrowser.open_new(f"http://127.0.0.1:{port}")).start()
                       ^^^^^^^^^^
NameError: name 'webbrowser' is not defined. Did you forget to import 'webbrowser'?
