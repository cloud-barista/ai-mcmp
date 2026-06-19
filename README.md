# AI-MCMP

AI-focused Multi-Cloud Management Platform integrating heterogeneous AI accelerators (GPUs, NPUs, ASICs) across multiple clouds.

## Overview

AI-MCMP simplifies deployment, operation, and management of AI workloads across heterogeneous cloud environments. This repository serves as the integration hub that aggregates all platform components as Git submodules.

## Components

### AI-MCMP Components

| Repository | Description |
|---|---|
| [ai-adm](https://github.com/cloud-barista/ai-adm) | Admin CLI for AI-MCMP platform |
| [ai-ui](https://github.com/cloud-barista/ai-ui) | Web Console UI for AI-MCMP platform |
| [ai-ops](https://github.com/cloud-barista/ai-ops) | Operations and workflow management |
| [ai-ha](https://github.com/cloud-barista/ai-ha) | High Availability management |
| [ai-app](https://github.com/cloud-barista/ai-app) | Application manager |
| [ai-o11y](https://github.com/cloud-barista/ai-o11y) | Observability and monitoring |

### Cloud-Barista Foundation

| Repository | Description |
|---|---|
| [cb-spider](https://github.com/cloud-barista/cb-spider) | Multi-cloud infrastructure connector |
| [cb-tumblebug](https://github.com/cloud-barista/cb-tumblebug) | Multi-cloud infrastructure management |
| [cm-beetle](https://github.com/cloud-barista/cm-beetle) | Cloud migration |

## Getting Started

Clone this repository with all submodules:

```bash
git clone --recurse-submodules https://github.com/cloud-barista/ai-mcmp.git
```

Or initialize submodules after cloning:

```bash
git clone https://github.com/cloud-barista/ai-mcmp.git
cd ai-mcmp
git submodule update --init --recursive
```

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.
