---
title: "GnuRAMage - The GNU RAM Disk Synchronization Tool"
date: 2025-06-02
---

GnuRAMage is a powerful Bash-based tool for synchronizing files between a high-speed RAM disk and traditional hard drives. It was created to help users manage large, multi-terabyte RAM disks, ensuring both performance and data safety.

## Key Features
- **Automatic File Copying:** Seamlessly copies files from hard disk to RAM disk for fast access.
- **Periodic Synchronization:** Regularly syncs changes from RAM disk back to persistent storage, protecting against data loss from power outages or crashes.
- **Exclusion Patterns:** Easily exclude files or directories from synchronization using flexible patterns.
- **INI Configuration:** Simple, human-readable configuration file for easy setup and customization.
- **Comprehensive Logging:** Multiple log levels, error-only logs, and detailed output for troubleshooting and monitoring.
- **Dry Run Mode:** Simulate operations without making changes, perfect for testing configurations.
- **One-time Mode:** Run a single synchronization cycle when needed.
- **Checksum Verification:** Optional integrity checks to ensure data consistency.
- **Script Generation:** Automatically creates standalone scripts for automation and integration with cron jobs.
- **Graceful Shutdown:** Handles interruptions and ensures a final sync before exit.

## Why Use GnuRAMage?
If you use a RAM disk to accelerate access to frequently used files, GnuRAMage ensures your data is always synchronized and safe. It protects your investment in high-speed memory by preventing data loss and automating tedious sync tasks. The tool is free, extensible, well-documented, and standards-compliant.

## Requirements
- Bash 4.0+
- rsync
- GNU/Linux
- Sufficient RAM (ideally in terabytes)

## Example Usage
- Start with default settings: `./gramage.sh`
- Run in dry-run mode: `./gramage.sh --dry-run --verbose`
- Use a custom config: `./gramage.sh --config mysetup.ini`
- Generate automation scripts: `./gramage.sh --script-gen-only`

## License
GnuRAMage is released under the GNU GPL v3.0 license.

For more details, visit the [GnuRAMage GitHub repository](https://github.com/FPGArtktic/GnuRAMage).
