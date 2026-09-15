# GunterChart for Windows

[Download GunterChart for Windows](https://github.com/elitehammer/GunterChart-Releases/releases/latest/download/GunterChart-Windows.zip)

No account needed. The updater finds your MT5 installation automatically. This repository contains compiled downloads only; application source remains private.

GunterChart - first-time setup (no account needed)

1. Download GunterChart-Windows.zip:
   https://github.com/elitehammer/GunterChart-Releases/releases/latest/download/GunterChart-Windows.zip
2. Right-click the ZIP and choose Extract All. Keep channel.json beside
   GunterChartUpdater.exe in the extracted folder.
3. Open GunterChartUpdater.exe. No GitHub sign-in or invitation is needed.
4. The updater finds MT5 automatically. If there is one installation it is
   selected for you; if there are several, choose the broker you want.
   Click Install for this MT5. If asked, open MT5 once in standard mode,
   then click Rescan. No folder paths need to be entered.
5. In MT5 Navigator, right-click Expert Advisors and select Refresh.
   Attach GunterChart > GunterChart to your chart. Replace a numbered version
   if one was already attached, and review the EA inputs.
6. For News, add https://nfs.faireconomy.media in MT5 Tools > Options >
   Expert Advisors > Allow WebRequest for listed URL.

Updates

The updater starts with Windows and checks every 15 minutes. Open GunterChart
Updater to Check for updates. Update updater installs a newer updater and
reopens it automatically; MT5 stays running.

For MT5 app updates, click Restart & update in GunterChart when convenient.
All EAs in that MT5 terminal pause briefly. Finish chart edits and pending
order previews first. Other MT5 installations are not restarted.

This version supports one standard MT5 installation per Windows login.
Portable installations are not supported. Restore previous version requires
MT5 to be closed and never force-closes it.

Migrating from updater v1/v2

Those versions used the old private GitHub channel and need this package once.
Exit the old updater from its tray menu before opening the new package.
Use Install for this MT5 for the same terminal. Existing chart attachment and
settings are retained. Public updater v3 and newer update without signing in.

This is a pilot for feedback. Test on a DEMO account first. Installation does
not place trades or enable Algo Trading. Initial Windows packages are not
Authenticode-signed. Download from the official link above. Updates retain
signature and file verification. Public downloads do not include source code.
