# GamePilot Nexus releases

**An AI that plays your PC games with you.** This is where Windows tester builds of GamePilot Nexus are published. There's no source code here.

## Get Nexus

The easiest way is **[gamepilotnexus.com](https://gamepilotnexus.com)**. Sign in with Google and the download starts. Your profile there is also where you manage your plan or enter a tester code.

Want the file straight from here? Open **[Releases](https://github.com/BurlyPunz/GamePilotNexus-releases/releases)** and take the newest build at the top.

## What's in each release

| File | What it is |
|---|---|
| `GamePilotNexus-Tester-<version>.exe` | The Windows installer |
| `SHA256SUMS.txt` | The installer's SHA256 hash so you can check your download |
| `TESTER-<version>.md` | What to try and how to report problems |

Check the hash in PowerShell:

```powershell
Get-FileHash .\GamePilotNexus-Tester-<version>.exe -Algorithm SHA256
```

It should match the line in `SHA256SUMS.txt`.

## Before you install

- Windows 10 (1809 or newer) or Windows 11, 64 bit.
- The installer isn't code signed yet, so Windows may warn you once. Click **More info**, then **Run anyway**. Only do that for a file from this page or the website.
- It installs just for you with no admin rights.
- First launch checks your PC and downloads the AI. That needs internet and free drive space.

Every build is installed on a clean Windows machine and started before it's published. Play on real PCs is still being tested, which is why these are early tester builds.

## Help

Use **Settings > Advanced > Diagnostics > Report a problem** in the app, or email support@gamepilotnexus.com.
