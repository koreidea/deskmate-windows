# HaiRobo Windows Companion

System-tray app that pairs the HaiRobo phone app with a Windows PC over local Wi-Fi
and answers screen-context questions.

## Install

Download the latest DeskmateSetup-x.y.z.exe from the Releases page and run it.
The build is currently unsigned, so Windows SmartScreen shows "unknown publisher" -
choose More info -> Run anyway. Installs per-user (no admin prompt).

After install, double-click the tray icon to open the QR pairing window and scan it
from the HaiRobo phone app on the same Wi-Fi.

## winget

Once accepted into the winget community repo:

    winget install Hairobo.WindowsCompanion