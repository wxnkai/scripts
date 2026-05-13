# Scripts

A structured collection of scripts organized by **problem domain**, built as a personal reference library and growing portfolio across cybersecurity and sysadmin disciplines.

## Repository Structure

```
scripts/
├── recon/                  # Active and passive reconnaissance
├── defense/                # Hardening, analysis, detection
├── forensics/              # Disk, memory, and log forensics
├── sysadmin/               # Automation and configuration
├── networking/             # Network utilities, packet work, diagnostics
├── osint/                  # Open-source intelligence gathering
└── utils/                  # Shared helpers and generic utilities
```

## Table of Contents

### 🔍 Recon
> Active and passive information gathering against targets.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### 🛡️ Defense
> Hardening, log parsing, anomaly detection, alerting integrations.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### 🔬 Forensics
> Artifact collection, timeline reconstruction, memory and disk analysis.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### ⚙️ Sysadmin

> Scripts that eliminate repetitive manual work and handle environment setup, package management, etc.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### 🌐 Networking
> Network diagnostics, traffic capture helpers, port utilities, protocol tools.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### 🕵️ OSINT
> Passive intelligence gathering using public sources and APIs.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

### 🔧 Utils
> Generic helpers with no specific domain — string manipulation, file ops, output formatting, shared functions sourced by other scripts.

| Script | Language | Platform | Description |
|--------|----------|----------|-------------|
| *(none yet)* | — | — |

## Script Conventions

Every script in this repo follows a consistent header format:

**Bash / Shell:**
```bash
#!/usr/bin/env bash
# -----------------------------------------------------------------------------
# Script  : script-name.sh
# Domain  : recon | defense | forensics | sysadmin | networking | osint | utils
# Desc    : One-line description of what this script does.
# Usage   : ./script-name.sh [options]
# Deps    : nmap, curl (list external dependencies)
# Author  : wxnkai
# -----------------------------------------------------------------------------
```

**Python:**
```python
#!/usr/bin/env python3
"""
Script  : script-name.py
Domain  : recon | defense | forensics | sysadmin | networking | osint | utils
Desc    : One-line description of what this script does.
Usage   : python3 script-name.py [options]
Deps    : requests, scapy (list pip packages)
Author  : wxnkai
"""
```

**PowerShell:**
```powershell
<#
.SYNOPSIS  One-line description.
.DOMAIN    sysadmin | defense | ...
.USAGE     .\script-name.ps1 [params]
.DEPS      None
.AUTHOR    wxnkai
#>
```

**Go**
```go
// -----------------------------------------------------------------------------
// Script  : script-name.go
// Domain  : recon | defense | forensics | sysadmin | networking | osint | utils
// Desc    : One-line description of what this script does.
// Usage   : go run script-name.go [options]  |  ./script-name [options]
// Deps    : github.com/some/package (list go.mod dependencies)
// Author  : wxnkai
// -----------------------------------------------------------------------------
```

## Languages Used

| Language | Use Case |
|----------|----------|
| `bash` / `sh` | Linux sysadmin, automation, recon pipelines |
| `python3` | Networking, OSINT, forensics, complex logic |
| `powershell` | Windows sysadmin, Active Directory, hardening |
| `go` | Performance-sensitive tools *(as needed)* |

## Disclaimer

The author assumes no responsibility for misuse. Always obtain explicit written authorisation before testing any system.

## License

[Apache 2.0](LICENSE)