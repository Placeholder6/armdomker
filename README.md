
<h1 align="center">
    extended zoomrec for arm	
</h1>

<h4 align="center">
	A all-in-one solution to automatically join and record Zoom meetings, modified for running on an ARM device (like a Raspberry Pi)
</h4>




---

- **Python3** - _Script to automatically join Zoom meetings and control FFmpeg_
- **FFmpeg** - _Triggered by python script to start/stop screen recording_
- **Docker** - _Headless VNC Container based on Ubuntu 20.04 with Xfce window manager and TigerVNC_
- **Telegram** - _Get notifications about meeting status_
---

![Join a test meeting](doc/demo/join-meeting.gif)

---

## Usage
Check the original [repository](https://github.com/kastldratza/zoomrec)

## Non ARM Usage:
You can use the additional features on any device. Clone the original repository, copy `zoomrec.py` from this repository into it and build the dockerfile.
