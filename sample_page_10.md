## Bug Defender — Cloud-Based Antivirus

Built a cloud-based antivirus system that scans files for malware using **three antivirus engines in parallel**. The design follows N-Version programming — running multiple independent detection engines increases the chance of catching threats that a single engine might miss.

**Tools:** Python, cloud architecture, parallel processing  
**Repo:** [GitHub](https://github.com/smit-collab/Cloud_based_antivirus)

---

## Overview

Bug Defender is designed to improve malware detection reliability by combining results from multiple scanning engines rather than relying on a single signature-based tool.

---

## Key Features

- **Multi-engine scanning** — three antivirus engines run in parallel on uploaded files
- **N-Version programming** — diverse detection approaches reduce single-point-of-failure risk
- **Cloud-based architecture** — scalable file scanning without local engine installation

---

## Why This Approach

Traditional single-engine antivirus tools can miss novel or polymorphic malware. Running multiple engines in parallel and aggregating their results provides a more robust detection layer — especially useful when engines use different heuristics and signature databases.

---

## Links

- [GitHub repository](https://github.com/smit-collab/Cloud_based_antivirus)
