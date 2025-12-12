# Accessible
A jailed filesystem utility for iOS 16+, utlizing the Shortcuts application.

[Latest Release](https://github.com/jailbreakdotparty/Accessible/releases/latest) • [Support Server](https://jailbreak.party/discord) • [Website](https://jailbreak.party)

>[!NOTE]
>This tool does **not** use any exploits, and therefore, does not give any elevated privileges. You can only read files that would usually be accessible from the sandbox.

## Readable Partitions
- `/System`: This directory, and almost all subfiles, are readable.
- `/Applications`: Note that reading this directory was blocked in iOS 26.1 and later, and will not show up on those versions.
- `/private/preboot`: This directory, and some subfiles, are readable.

## Tools
- Filesystem Browser: Browse, view, and extract files from any partitions listed in the "Readable Partitons" section.
- Internal App Manager: Open applications that aren't normally presented to the user. You can also view & export the bundles of those applications. This has very similar functionality to [Bridge](https://github.com/jailbreakdotparty/Bridge).
- MobileGestalt Extractor: Extract your MobileGestalt quickly & easily with the use of two methods (Content Graph or Freeform). Getting the MobileGestalt is necessary for tools such as [Nugget](https://github.com/leminlimez/Nugget).
- MobileGestalt Inspector: Get device details, enabled/disabled features, and more. The "Device Report" section can allow you to see what things you may have enabled on your device with [Nugget](https://github.com/leminlimez/Nugget).

## QoL Features
- Favorites: Easily access any directory you'd like by favoriting it.

## Troubleshooting
- Accessible is hanging/taking too long to do something: Usually, loading some directories take a while. If it hangs for too long, simply try again. If that doesn't help, restart the Shortcuts app from the app switcher and try again.
- The "Content Graph" method of exporting MobileGestalt isn't working: Kill the Shortcuts app from the app switcher and try again. If that doesn't work, try the freeform method instead.
