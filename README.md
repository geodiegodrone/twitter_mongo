# Twitter Mongo Import Practice

**Educational Twitter/X API to MongoDB ingestion exercise**

[![Python](https://img.shields.io/badge/python-3.11%2B-blue)](requirements.txt)
[![Security](https://img.shields.io/badge/security-env%20based%20secrets-green)](.env.example)

This repository contains an academic example for loading social-media account data into MongoDB. API keys and MongoDB credentials are read from environment variables instead of being committed in source code.

## Security First

Never commit API keys, tokens, passwords, MongoDB URIs, or exported `.env` files.

```bash
cp .env.example .env
python -m pip install -r requirements.txt
python -m py_compile TwitterMongo01MBID.py
```
