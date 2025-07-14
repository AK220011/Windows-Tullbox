# Windows-Tullbox
Hand picked tools and services for a better windows experience. 

Emojis for easy installation through the two app installers with three emojis. If both emojis, it means it is on both. 
Sometimes christitus has issues where it asks for user credentials so Patch My PC is prefferable and is what I use.

terminal admin --> irm https://massgrave.dev/get | iex (activation windows/office)
                            --> irm christitus.com/win | iex (app installer/updater)🥶🥶🥶
-----------------------------------------------
- Browsers:           
- DuckDuckGo    
- Brave🥵🥶
- Chrome🥵🥶
- Vivaldi🥵🥶
- Firefox🥵🥶(use betterfox user.json)
- Waterfox🥵🥶

- Needs:
- Patch My PC Home Updater (app installer/updater)🥵🥵🥵
- qBittorrent🥵🥶
- OnlyOffice🥵🥶
- Steam🥵🥶
- Geek Uninstaller 🥵(uninstall apps with this!)
- WizTree🥵🥶(easy storage management)
- VLC🥵🥶
- 7zip🥵🥶
- OOShutUp10++🥵 (disable windows telemetry, per user or all)

Wants:
ImageGlass🥵🥶
Rufus🥵 (.iso usb installer)
Ditto🥵🥶 (clipboard history saver)
PDFgear🥶/PDF-XChange Editor🥵
Discord🥵🥶
Vesktop🥶 (discord foss, free modded nitro)
Bitwarden🥵 (free password manager)
Stremio🥶 (+Alldebrid, 3€/m watch any torrent on demand)
File-Converter app🥶 (context menu any file converter)
Files app🥶/ Opus directory(50€/lifetime) (explorer alternatives)
LocalSend🥶 Android/macOS/iOS/Linux/Windows (local-filesharing)
Netlimiter (internet traffic control)
Notepad ++🥵🥶
Flameshot🥶 (editable screenshots)
HWiNFO64🥵🥶
Blitz (LoL builds)
4K Video Downloader🥵 (youtube extract)
Twinkle Tray🥶 (taskbar screen brightness / MSstore)
Everything search🥵🥶(search for any file on pc quickly)
Equalizer APO🥶(EQ headphones/speakers)
OBS Studio🥵🥶(record/stream)
Windows mods: RetroBar(win7/xp taskbar) / TransluscentTB🥶/ SoundManager / EarTrumper🥶
🥵EA/Epic/GOG/GeForce/Logitech/Ubisoft/Battle.net🥵
Windows Media Creation Tool 10/11🥵(make .iso and use with rufus)
Recuva🥵 (recover deleted files)
Picocrypt(portable)/Cryptomator🥵/VeraCrypt🥵 (foss file encryption)
-----------------------------------------------
Services:
Video Editors: VSDC(free, pro32€/y) / Davinci Resolve🥵 / Kdenlive🥵🥶(foss) / Filmora(80€/lifetime)  / PowerDirector(yarr?) / ShotCut (foss) / Movavi Video Editor (100€/lifetime)
Paint: Krita 🥵🥶(foss) / Clip Studio Paint(50€/lifetime) / Sketchbook(MS store 25€/lifetime)
Debrid: Alldebrid(3€/m)
VPN: IVPN (2$/week, 6$/month 140$/3y) Mullvad/AzireVPN(5€/m)
DNS: ControlD (use 1hosts-lite)
AV: Sophos Home Premium (better than Windows Defender because it has behaviour blocking and cheaper than bitdefender, kaspersky, eset, emsisoft)
Mail: Posteo(12€/y)+ eM Client🥵(IMAP)
Sync: SyncBackFree
Cloud: Filen(100GB/30€/stackable/lifetime)
Upload files: swisstransfer.com, wormhole.app, 
-----------------------------------------------
https://kumu.io/Windscribe/vpn-relationships (companies connected to various vpn services)
https://github.com/TunnlTo/desktop-app
-----------------------------------------------
pirateshit:
AVOID REPACKMASTER(onyhash), CONTAINS aurotun info stealer in all uploads!
1337x/TPB/rarbg not yet banned malware uploader "onyhash" (repackmaster fakes) AVOID!
Not detected by any AV database yet.

APPS:
https://pesktop.com/en/
https://lrepacks.net/
https://4download.net/
https://filecr.com/en/
https://programs.themicrotech.net/
https://appdoze.net/

GAMES:
https://fitgirl-repacks.site/
http://www.skidrowreloaded.com/

ANIME:
https://dkb.si/index
https://nyaa.si/
https://subsplease.org/

TV:
https://psa.wf/
https://eztvx.to/home

audioshit:
https://g-meh.com/library/windows
https://www.magesy.blog/

TORRENTS:
https://knaben.org/ (1337x/TPB/rutracker)
https://ext.to/
https://torrentquest.com/
https://uindex.org/
https://knaben.xyz/
https://bitsearch.to/
https://btdig.com/ (unsafe, only last resort)

SUBTITLES:
https://www.opensubtitles.org/en/search/subs
https://subsource.net/info
https://github.com/fmhy/FMHY
https://github.com/fmhy/FMHY/wiki/%F0%9F%8C%80-Torrenting

List of on demand streamers (anime,movies,shows):
http://tbcpl.lol/

Privacy Tools:
https://awesome-privacy.xyz
-----------------------------------------------
Shit Hit the Fan Portables:
1.Norton Power Eraser
2.Adlice Diagnostic Portable
3.Emsisoft Emergency Kit🥵
4.Sophos ScanAndClean

Malware/Diagnostics:
Adlice Diagnostic Portable
RogueKillerPE64
Autoruns🥵🥶
Adlice UCheck Portable
-----------------------------------------------
Windows fixes:
SFC (System File Checker): This command scans and repairs corrupted system files. To run it, open CMD and type `sfc /scannow`

DISM (Deployment Image Servicing and Management): This tool can be used to repair and restore the Windows image. In CMD, type `DISM /Online /Cleanup-Image /RestoreHealth`

CHKDSK (Check Disk): This command checks and fixes errors on a hard drive. In CMD, type `chkdsk C: /f` to check and fix the C drive

Reset Windows: Settings->Windows Update->Advanced Options->Recovery->Reset this PC

Bypass TPM, CPU, RAM, and Secure Boot: 
Shift + F10 to open the Command Prompt.
Type regedit and press Enter
HKEY_LOCAL_MACHINE\SYSTEM\Setup, 
New registry key named LabConfig
DWORD value name:
BypassTPMCheck value to 1
BypassSecureBootCheck value to 1
BypassRAMCheck value to 1
BypassCPUCheck value to 1

Bypass network req on install: 
shift+f10 (for cmd)
OOBE\BYPASSNRO
-----------------------------------------------
Secure DNS:
https://controld.com/free-dns
76.76.2.38     2606:1a40::38      https://freedns.controld.com/x-1hosts-lite (doh/3)
76.76.10.38   2606:1a40:1::38     x-1hosts-lite.freedns.controld.com (dot/q)

Lists:
https://hblock.molinero.dev
https://firebog.net
https://o0.pages.dev
https://energized.pro
https://github.com/hagezi/dns-blocklists
https://blocklistproject.github.io/Lists

Blocklists (adblocker):
https://o0.pages.dev/Lite/adblock.txt

https://hblock.molinero.dev/hosts_adblock.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt
https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-adguard.txt
https://raw.githubusercontent.com/liamengland1/miscfilters/refs/heads/master/antipaywall.txt
https://raw.githubusercontent.com/yokoffing/filterlists/refs/heads/main/antipaywall_filters_without_element_hiding.txt

https://raw.githubusercontent.com/AdguardTeam/cname-trackers/master/data/combined_disguised_trackers.txt

Blocklists (dns blocking):
https://o0.pages.dev/Lite/hosts.txt

https://big.oisd.nl
https://hblock.molinero.dev/hosts
https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/multi.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.xiaomi.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.winoffice.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.vivo.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.samsung.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.roku.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.oppo-realme.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.lgwebos.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.huawei.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.apple.txt
https://raw.githubusercontent.com/hagezi/dns-blocklists/refs/heads/main/hosts/native.amazon.txt

