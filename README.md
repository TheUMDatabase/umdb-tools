# UMDB Tools

This repository contains various scripts used by umdatabase.net for generating and managing submissions

Given an ISO file, it will generate a json file with the following informationg
- File size
- Hashes (MD5, CRC32, SHA1, SHA256)
- ISO PVD Hexdump
- SFO information
- File tree with individual SHA1 checksums, date and file size

# Requirements

- Python 3 (>= 3.6)
- pycdlib

# Usage

`python3 umdb_gen_submission.py <iso_file> [--out <output_file>]`
