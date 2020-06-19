# AutopilotDeviceConfiguration
A modified version of AutopilotBranding (https://github.com/mtniehaus/AutopilotBranding) which configures a device during Windows Autopilot based on its geographical location.

I've removed items I didn't want/need to customise in my version, such as the Start Menu.

# Usage
1. Add/update Config.xml with Geo ID elements for the location(s) you need.
2. Add the language pack file(s) to the LPs folder.
3. Create a language Language XML file for each.
4. Edit the Associations.xml file with your preffered associations.
5. Create a .intunewin file and add as a Win32 application to Intune (you can follow the AutopilotBranding on the best way to do that)
