# Sploit Test
A tester tool for the bug PoC released by Synacktiv for 15.0 - 15.4 beta 3

iOS 15.4 patched a kernel vulnerability introduced in iOS 15.0 beta that causes corruption of ipc_kmsgs which leads to powerful primitives that can be used for local privilege escalation from WebContent and app Sandbox.

Synacktiv have posted a tweetable PoC here: https://twitter.com/Synacktiv/status/1504142757157384198 and I've put it together in a small tester application.

With this app you can test if your device is vulnerable to this bug. If it is, it can be used for jailbreaking on your device!

## How to use:

Sideload the application and run it. Press the Reboot button. If the device reboots, it's vulnerable. If nothing happens, it's not.

## Credits 

* App developed by AppInstaller iOS (@AppInstalleriOS): https://twitter.com/AppInstalleriOS
* Original App developed by GeoSn0w (@FCE365): https://twitter.com/FCE365
* DebianArch Helped Make It Work (@DebianArch): https://twitter.com/DebianArch
* PoC by @Synacktiv: https://twitter.com/Synacktiv/status/1504142757157384198
