def ports():
    detected_port = (
        os.environ.get("SERIAL_PORT")
        or serial_handler.auto_detect_port()
        or "ttyUSB0"
    )
    return jsonify(ports=[{"device": detected_port, "desc": "Mạch IMU"}])

    port = data.get("port") or os.environ.get("SERIAL_PORT") or serial_handler.auto_detect_port()
