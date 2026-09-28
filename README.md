# edgelet releases

Pre-built packages of **edgelet**, the toolkit for the *Machine Learning for IoT* labs
(Uppsala University): data acquisition, training and deployment of gesture models on the
Arduino Nano 33 BLE.

## Install

Python 3.10–3.12 on Windows, macOS or Linux. Pick the newest release on the
[Releases page](https://github.com/lishenghui/edgelet-releases/releases); its notes show the exact command:

```bash
python -m venv edgelet-env
edgelet-env\Scripts\activate            # macOS / Linux: source edgelet-env/bin/activate
pip install "edgelet[train] @ https://github.com/lishenghui/edgelet-releases/releases/download/<version>/edgelet-<version>-py3-none-any.whl"
```

Then follow the lab instructions on Studium.
