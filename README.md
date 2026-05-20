# CTI Assessment Report

This repository contains a CTI assessment for a Lumma Stealer campaign.

## Files

- `yara.txt` — YARA rules for Lumma Stealer detection.
- `screenshots/` — evidence and analysis images.

## Summary

The report includes rules for:
- C2 communication detection
- campaign infrastructure domains
- agent credentials and session tokens
- fingerprinting/exfiltration behavior
- DGA fallback indicators
- post-exfiltration concealment

## How to use

1. Open `yara.txt`.
2. Load the rules into your detection tool.
3. Scan traffic or endpoint data for matching strings.

## Author

Adebayo