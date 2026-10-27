# Personal Scoop Bucket

Custom and modified Scoop application manifests.

## Applications

| App | Description | Changes / Customizations |
| --- | --- | --- |
| `ludusavi` | Backup tool for PC game saves | Custom persist directories and files |
| `revouninstallerpro` | Software uninstaller with advanced registry/file cleanup | Custom portable manifest |
| `stirling-pdf` | Locally hosted web application for PDF operations | Custom persist configs and shortcuts |

## How to Install

Add this bucket to Scoop:

```powershell
scoop bucket add personal https://github.com/0xBaselessProjects/Scoop-Extras.git
```

Install an application from this bucket:

```powershell
scoop install personal/<app>
```

For example:

```powershell
scoop install personal/ludusavi
scoop install personal/revouninstallerpro
scoop install personal/stirling-pdf
```

## Automated Updates

Manifests in this bucket are autonomously tracked and updated using GitHub Actions (Excavator) running Scoop's `checkver` on a schedule.
