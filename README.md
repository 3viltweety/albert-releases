# Albert: releases

Albert is a Windows desktop app that controls Claude Code by voice, behind a futuristic HUD, with the persona of a calm, polite, dry-witted British butler.

This repository only holds the **installer and the update files**. The source code is private.

## Installing

1. Download `Albert-Setup-<version>.exe` from the [latest release](https://github.com/3viltweety/albert-releases/releases/latest) and run it.
   The installer is not code-signed: Windows SmartScreen shows a warning → *More info → Run anyway*.
2. Albert uses your existing Claude Code login. Never logged in? Run `claude` in a terminal once, or enter an Anthropic API key under *Settings → Claude Code*.

## Updates

You install Albert once. From 0.5.0 on, it checks this repository for new versions and downloads them as small **patches** (only the changed parts). They are applied when Albert restarts, or via *Settings → Updates → Restart & apply*. *Settings → Updates → Patch notes* shows what each version changed.

Each release contains the installer, its `.blockmap` and `latest.yml`; the app needs all three. Old releases stay available, because a patch is built from the installed version.
