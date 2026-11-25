# hdd-health-check

Automated disk analysis and interactive storage recovery reporting tool for macOS.

## Quick Start

To re-run the storage scan and regenerate the interactive report:

```bash
cd ~/Workspaces/disk-health-utils
.venv/bin/python generate_disk_report.py
open disk_space_report.html
```

## Generated Files
- `disk_space_report.html`: Standalone, interactive HTML report with dynamic storage savings calculator and one-click copyable cleanup commands.
- `generate_disk_report.py`: Python scanner targeting macOS APFS volumes, Photos originals, developer caches, and application support bloat.
