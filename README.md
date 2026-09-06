<div align="center">  
    <h1>Accessible</h1>
    <p>Jailed filesystem utility for iOS 16+, which uses the Shortcuts app.</p>
    <a href="https://github.com/jailbreakdotparty/Accessible/releases/latest"><img alt="GitHub Downloads (all assets, all releases)" src="https://img.shields.io/github/downloads/jailbreakdotparty/Accessible/total?style=flat-square&color=AE51DC"></a>
    <a href="https://github.com/jailbreakdotparty/Accessible/stargazers"> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/jailbreakdotparty/accessible?style=flat-square&color=%23FFD300"></a> 
    <a href="https://jailbreak.party/discord"><img alt="Discord" src="https://img.shields.io/discord/1349128546072793218?style=flat-square&logo=discord&logoColor=FFFFFF&color=5865F2"></a> 
    <a href="https://jailbreak.party"><img alt="Static Badge" src="https://img.shields.io/badge/jailbreak.party-blue?style=flat-square&label=%20&color=3868DB"></a>
</div>

>[!NOTE]
>This tool does **not** use any exploits, and therefore, does not give any elevated privileges. You can only read files that would usually be accessible from the sandbox, hence the key word "jailed."

### Usage & Installation
- Installation is easy! Just download the shortcut from the latest release tag and import it into the Shortcuts app. Then, run the Shortcut. If you're on iOS 16.0 - iOS 26.0.1, the shortcut will hang for a while during setup, as it has to fetch applications from the filesystem. Be patient!
- Since this is a shortcut, browsing certain directories with tons of files will take a while to load, so the shortcut may become unresponsive.

### Features
- Filesystem Browser
- System App Opener & Extractor (like [Bridge](https://github.com/jailbreakdotparty/Bridge).
- Gestalt Extractor & Inspector
- Apple Watch Gestalt Extraction (hooray)

### Readable Paths
- `/System`: This directory, and almost all subfolders, are readable.
- `/Applications`: Fully readable **on iOS 16.0-26.0.1.**
- `/private/preboot`: This directory, and some subfolders, are readable.
