---
description: Essential information for becoming a compute provider on Phala Network.
title: Requirements in Phala
---

Phala Network is centered around Dstack﻿, a zero-trust framework for confidential containers that provides scalable and secure confidential computing. Phala’s hardware requirements align with the [Dstack﻿ specifications](https://docs.phala.com/dstack/getting-started).



## Basic Requirements

Phala Network has evolved to use Dstack﻿ as its core architecture. As a result, all hardware requirements for running Phala Workers (compute nodes) follow the standards set by Dstack﻿ for confidential computing.

## TGX Function

- Workers must run on Intel CPUs supporting TDX (Trust Domain Extensions), which provide hardware-based trusted execution environments (TEEs).
- Ensure TDX is enabled in the server BIOS for proper secure container execution.

## Stable Network

- Stable network with at least 1 Gbps bandwidth.
- A public IPv4 address is mandatory for node accessibility.
- Owning a domain and configuring DNS is recommended for gateway TLS setup.

## OS Requirements

- Recommended OS is **Ubuntu 24.04 Server LTS** with Linux kernel **6.8+**.
- Desktop OS versions are less stable and not recommended.

## Device Hardware Specifications

| Deployment Type             | CPU                                    | Memory                     | Storage                | Additional Notes             |
| :-------------------------- | :------------------------------------- | :------------------------- | :--------------------- | :--------------------------- |
| Local Development           | Intel CPU with TDX                     | ≥16 GB                     | ≥100 GB SSD            | For development/testing only |
| Physical Server             | Intel Xeon 5th/6th Gen (TDX supported) | ≥16 GB (32 GB recommended) | ≥100 GB NVMe SSD       | Requires public IPv4 IP      |
| Cloud Hosting (Phala Cloud) | N/A (virtualized)                      | Managed by Phala Cloud     | Managed by Phala Cloud | Simplified deployment        |

