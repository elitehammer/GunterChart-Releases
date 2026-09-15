# GunterChart for invited testers

[Download the latest app](https://github.com/elitehammer/GunterChart-Releases/releases/latest) and choose **GunterChart-Windows.zip** under Assets.

GunterChart - first-time setup

1. Accept the private GitHub invitation using your own GitHub account.
2. Download GunterChart-Windows.zip from:
   https://github.com/elitehammer/GunterChart-Releases/releases/latest
3. Extract all files into a folder. Keep channel.json beside GunterChartUpdater.exe.
4. Open GunterChartUpdater.exe and choose Sign in with GitHub.
   Enter the code shown in the updater on GitHub and authorize GunterChart Updates.
5. Select the correct MT5 installation and click Install for this MT5.
6. In MT5 Navigator, right-click Expert Advisors and select Refresh.
   Attach GunterChart > GunterChart to your chart. Replace a numbered GunterChart
   version if one was already attached, and review the EA inputs.
7. For News, add https://nfs.faireconomy.media in MT5 Tools > Options >
   Expert Advisors > Allow WebRequest for listed URL.

Updates

The updater starts with Windows and checks every 15 minutes. When GunterChart
shows New update available, click Restart & update when convenient. All EAs
in that MT5 terminal pause briefly. Save or cancel unfinished chart edits and
pending order previews first. No other MT5 installation is restarted.

You can open GunterChart Updater from the Windows notification area to check
for updates, sign in again, or restore the previous version with MT5 closed.
Restore never force-closes MT5. The first updater supports one standard MT5
installation per Windows login; portable installations are not supported yet.

This is a pilot for feedback. Test on a DEMO account first. Installation does
not place a trade or enable Algo Trading. The initial Windows package is not
Authenticode-signed. Download only through the invited private repository.
The helper currently updates the EA; a new helper requires a new package.
