Valbuena Client - macOS Apple Silicon

This client is built for Apple Silicon Macs.

Why macOS may block it:
macOS may show a warning because this app is not currently notarized through Apple Developer ID. This does not mean the client files are missing. It means macOS cannot verify the developer signature yet.

How to open it:

1. Unzip the downloaded file.
2. Open the ValbuenaClient-macOS-AppleSilicon folder.
3. Open Terminal.
4. Type:

cd 

Then drag the ValbuenaClient-macOS-AppleSilicon folder into Terminal and press Enter.

5. Run this command:

xattr -cr ValbuenaClient.app data modules mods init.lua

6. Then run:

chmod +x ValbuenaClient.app/Contents/MacOS/OTClient

7. Open the app again:

open ValbuenaClient.app

After this, the client should open normally.

Note:
This is a temporary macOS opening step until the client is signed and notarized with an Apple Developer ID.
