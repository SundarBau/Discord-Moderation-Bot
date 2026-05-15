# Advanced Discord Moderation Bot

A powerful all-in-one Discord moderation and security bot built using Python and `discord.py`.

This bot provides advanced moderation tools, auto-moderation, security systems, detailed logging, warning management, anti-raid protection, and a fully customizable permission system.

---

# Features

## Moderation Commands
- `/kick`
- `/ban`
- `/softban`
- `/unban`
- `/mute`
- `/unmute`
- `/timeout`
- `/untimeout`
- `/warn`
- `/warns`
- `/clearwarn`
- `/purge`
- `/lock`
- `/unlock`
- `/slowmode`

---

# Auto Moderation

### Anti-Spam Protection
Automatically detects spam messages and punishes users.

### Bad Word Filter
Includes:
- English bad words
- Nepali bad words
- Custom bad word support

### Link Protection
Blocks unauthorized invite links and suspicious URLs.

### Mass Mention Protection
Prevents abuse of:
- `@everyone`
- `@here`

### Auto Punishments
- Auto warn
- Auto mute
- Configurable warning limits

---

# Security System

## Anti Raid
Detects mass joins and automatically kicks suspicious users.

## Alt Detection
Automatically removes newly created accounts.

## Security Scan
Use `/securityscan` to scan:
- Bots
- Admins
- New accounts
- 2FA status
- Verification settings

---

# Logging System

Detailed moderation logs for:
- Message edits
- Message deletions
- Member joins
- Member leaves
- Bans
- Unbans
- Mutes
- Warnings
- Auto moderation actions

Set log channel with:
```bash
/setlogchannel
