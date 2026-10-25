# 🌪️ Data Training (Project BT)

This repository hosts the compressed training bundle and datasets for Project BT.

## 📦 Training Bundle: `data_storm.tar.gz`
The full pre-training dataset and deployment environment is available in **Releases**:
- **Raw Unpacked Size:** ~49.5 GB
- **Total Tokens:** 26.56 Billion tokens (25.77B train + 791M val, `uint16` binary matrices)
- **Included Files:**
  - `data/train.bin` (48.0 GB)
  - `data/val.bin` (1.47 GB)
  - `data/binary_packing_manifest.json`
  - `tokenizer/bt_tokenizer.json` (32,000 vocab BPE)
  - `model/transformer.py`
  - `model/train_h100.py`
  - `start_train.sh`
  - `README_SSH.md`

## 🚀 How to Extract
```bash
tar -xzf data_storm.tar.gz
```
