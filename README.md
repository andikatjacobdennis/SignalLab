# Signal Lab

Releases of **Signal Lab**, a Windows workbench for Bank Nifty: live option chain and charts, a quant signal, bar replay,
Strategy Lab (Signal Script), the market map and exit odds, with Zerodha Kite.

This repository holds the installers only; the source is private.

## Install

1. Download `SignalLab-<version>.msi` from the [latest release](https://github.com/andikatjacobdennis/SignalLab/releases/latest).
2. Run it. The installer is not code-signed yet, so Windows SmartScreen asks first: **More info › Run anyway**.
3. Start **Signal Lab** from the Start menu or the desktop.

Needs 64-bit Windows 10 or 11; .NET is included. A portable zip is in each release too.

## Activation

Signal Lab needs a **license for your PC** to run. On first start it shows your PC's **machine code**
(`SLAB-XXXX-XXXX-XXXX-XXXX`, with a Copy button): send it to the publisher, then choose **Load license file…** and pick the
`.lic` file you receive. A license is valid for **one year**; Help › License shows its dates and loads a renewal. Your license
is kept in `C:\Trading\license` and survives updates and reinstalls.

## Updates

Signal Lab checks this repository once a day (**Help › Check for updates**) and installs a newer version after checking its
SHA-256. Your data, models, settings, keys and license in `C:\Trading` are never touched by an install, update or uninstall.

## Checksums

Each release has `SHA256SUMS.txt`: `sha256sum -c SHA256SUMS.txt`, or `Get-FileHash SignalLab-<version>.msi` in PowerShell.

Signal Lab is research software, not investment advice; trading derivatives carries risk.