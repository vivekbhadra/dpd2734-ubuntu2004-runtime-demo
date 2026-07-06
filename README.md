# DPD-2734 Ubuntu 20.04 Runtime Demo

This repository contains a binary-only Ubuntu 20.04 runtime demo package for validating the DPD-2734 CAN data provider flow.

The package is provided for evaluation and demonstration only. It does not include source code, build files, internal design documentation, or implementation details.

## Contents

- `DPD-2734-ubuntu20.04-runtime-demo.tar.gz`
- `SHA256SUMS.txt`
- `EVALUATION_NOTICE.txt`

## Target Environment

This package is intended for:

- Ubuntu 20.04
- WSL2 Ubuntu 20.04 or native Ubuntu 20.04
- GLIBC 2.31
- SocketCAN virtual CAN interfaces
- `can-utils`

## Verify Package Integrity

```bash
sha256sum -c SHA256SUMS.txt
