---
title: "AutoGit-o-Matic"
date: 2025-06-02
---

AutoGit-o-Matic is a Bash script designed to automate Git operations across multiple repositories. It is especially useful for developers who work on several projects or use multiple computers, ensuring all repositories stay up to date with minimal effort.

## Key Features
- **Batch Git Operations:** Pull or fetch updates from multiple repositories with a single command.
- **Automatic Repository Discovery:** Scans directories to find all Git repositories automatically.
- **Flexible Configuration:** Uses a simple INI file to specify which repositories to manage and how to log operations.
- **Logging:** Supports both TXT and JSON log formats for easy tracking and auditing.
- **Dry-Run Mode:** Simulate operations without making any changes, perfect for testing.
- **Verbose Output:** Get detailed information about each operation for troubleshooting.
- **Cron Integration:** Easily set up scheduled syncs using cron jobs for full automation.

## Example Usage
- Run with default config: `./autogit-o-matic.sh`
- Simulate actions: `./autogit-o-matic.sh --dry-run --verbose`
- Use a custom config: `./autogit-o-matic.sh --config myconfig.ini`
- Log to a file: `./autogit-o-matic.sh --log-file autogit.log`

## Cron Example
To run every hour:
```
0 * * * * /path/to/autogit-o-matic.sh --log-file /path/to/autogit.log
```

## License
AutoGit-o-Matic is released under the GNU GPL v3.0 license.

For more details, visit the [AutoGit-o-Matic GitHub repository](https://github.com/FPGArtktic/AutoGit-o-Matic).
