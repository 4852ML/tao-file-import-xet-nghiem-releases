# Tạo file import xét nghiệm — Official Releases

This is the official update relay for the portable Windows application **Tạo file import xét nghiệm**.

- Publisher: **Lê Minh Nhật**
- Organization: **OPC Trạm Y tế phường Tân Định**
- Current update status: **disabled until the next tested release is published**

## What this repository contains

- `latest.json`: the stable-channel update signal checked by the application.
- Official portable Windows release files and their checksums, added only after testing.
- Release notes and authenticity information.

This repository does **not** contain application source code, patient data, clinic credentials, passwords, eClinica exports, Trinasoft files, or hospital PDF results.

## Permanent update signal

`https://raw.githubusercontent.com/4852ML/tao-file-import-xet-nghiem-releases/main/latest.json`

The application must ignore a manifest when `enabled` is `false`, when its cryptographic signature is invalid, or when the downloaded executable does not match the published SHA-256 checksum.

## Authenticity

Use only releases published from this repository and identified inside the application as:

**Lê Minh Nhật — OPC Trạm Y tế phường Tân Định**

Copies with a different publisher, altered checksum, or invalid signature are not official releases.
