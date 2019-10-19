## Installation

```bash
sudo apt install python3-click python3-dev libmagic-dev

pip3 install python-libmagic
```

## Usage

### Report

```bash
python3 report.py 'path-to-datasets' 'path-to-tectonic-engine1'
python3 report.py 'path-to-datasets' 'path-to-tectonic-engine2'
```

### Compare results

```bash
python3 compare.py 'path-to-report1.jsonl' 'path-to-report1.jsonl'
```

### Clean garbage

```bash
python3 gc.py
```
