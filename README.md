# Forensic Version Checker
Script that checks for available updates for the most commonly used Digital Forensics tools.

![FVC screenshot](https://github.com/jankais3r/Forensic-Version-Checker/blob/master/screen.png)


![CLI interface](https://github.com/jankais3r/Forensic-Version-Checker/blob/master/cli.png)

## Supported tools
- ALEAPP
- Arsenal Image Mounter
- Atola TaskForce
- Autopsy
- AVML
- AXIOM
- Belkasoft Evidence Center
- BlackLight
- CAINE
- CyberChef
- DEFT
- ElcomSoft iOS Forensic Toolkit
- EnCase
- ExifTool
- Eric Zimmerman's Forensic Tools
- Forensic Email Collector
- Forensic Explorer
- Forensic Falcon Neo
- F-Response
- FTK
- FTK Imager
- hashcat
- HstEx
- iLEAPP
- IREC
- iVe
- Kali
- KAPE
- LiME
- MacQuisition
- MobilEdit
- Mount Image Pro
- NetAnalysis
- NirSoft Launcher
- NSRL hash list
- OSForensics
- Oxygen Forensic Detective
- Paraben E3
- Passware
- Physical Analyzer
- The Sleuth Kit
- TZWorks
- UFED 4PC
- USB Detective
- VeraCrypt
- XAMN
- X-Ways

If your favorite tool is missing, feel free to open an Issue and provide me with a link to that tool's website.

## Dependencies

You can install the dependencies with:

```
pip3 install -r requirements.txt
```

or individually with:

```
pip3 install tabulate
pip3 install grequests
pip3 install beautifulsoup4
pip3 install tkScrolledFrame
```

## Tested with Python 3.7 under
- Windows 10
- Ubuntu WSL (requires X server, e.g. Xming)
- Ubuntu 18.04
- macOS Mojave
- [Pythonista](https://apps.apple.com/us/app/pythonista-3/id1085978097) iOS app (use the `fvc_pythonista.py` script)

You can create the following shortcut to launch FVC on Windows without having the Python console displayed (GUI-only mode).

![FVC shortcut](https://github.com/jankais3r/Forensic-Version-Checker/blob/master/shortcut.png)
