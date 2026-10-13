# PYTHON-NIDS

# Python Network Intrusion Detection System (NIDS)

A beginner-friendly Network Intrusion Detection System built
with Python, Scapy and Streamlit.

## Features

- Live IP packet monitoring
- Basic TCP port scan detection
- High-traffic threshold alerts
- Security alert logging
- Streamlit dashboard for alert history
- CSV export for recorded alerts

## Technologies

- Python
- Scapy
- Streamlit
- Pandas
- Kali Linux

## Setup

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd Python-NIDS
```

Create a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
pip install scapy streamlit pandas
```

## Run the NIDS

```bash
sudo ./venv/bin/python nids.py
```

## Run the Dashboard

Open another terminal:

```bash
cd Python-NIDS
source venv/bin/activate
streamlit run dashboard.py
```

Open the local URL shown by Streamlit in your browser.

## Disclaimer

For educational purposes and authorized network monitoring
only. Detection rules are basic and may produce false positives.
