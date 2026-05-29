# cerio-obsidian-sync Scoop Bucket

Scoop bucket for [osync](https://github.com/AlexCas/cerio-obsidian-sync) — Obsidian vault synchronization tool.

## Install via Scoop

```powershell
scoop bucket add cerio-obsync https://github.com/AlexCas/scoop-cerio-obsync
scoop install osync
```

## Usage

```bash
# Initialize a vault
osync init

# Configure server connection
osync config set server_url http://your-server:8080
osync config set api_key osync_your_key_here

# Sync your vault
osync sync
```