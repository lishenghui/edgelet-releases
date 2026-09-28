# edgelet releases

Pre-built packages of **edgelet**, the toolkit for the *Machine Learning for IoT* labs
(Uppsala University): data acquisition, training and deployment of gesture models on the
Arduino Nano 33 BLE.

## Install

Python 3.10–3.12 on Windows, macOS or Linux:

```bash
python -m venv edgelet-env
edgelet-env\Scripts\activate            # macOS / Linux: source edgelet-env/bin/activate
pip install "edgelet[train]" -f https://lishenghui.github.io/edgelet-releases/
```

This installs the newest release. To update later, run the same `pip install` with `-U`.
All versions: [Releases](https://github.com/lishenghui/edgelet-releases/releases).

Then follow the lab instructions on Studium.
