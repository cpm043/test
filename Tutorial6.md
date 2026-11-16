# Tutorial 6 Activities
Wireless Networks

# Task 1.  View Wi-Fi Details
Explore the Wi-Fi details of your own device. If you have a laptop (or PC with Wi-Fi) try to use PowerShell with the WifiTools module (see commands below).
Install-Module WiFiTools
Show-WiFiState
Scan-WiFiAPs
Show-WiFiInterface
Get-WiFiLog | Select-Object -First 10

Otherwise, use your mobile phone to see nearby Access Points.
Try to collect the following information about 2 or 3 different APs:
•	SSID: HoundNet
•	BSSID
•	Frequency band
•	Channel
•	Data rate you can connect with
While not required, the WiFi Analyzer app on Android shows useful information.
In your journal: List information found about at least one AP.
Alternative Options…
1.	Use a Mac (if available): Hold Option (⌥) and click the Wi-Fi icon in the menu bar. It displays SSID, BSSID, Channel, Band, and Tx Rate all on one screen.
2.	Open poweshell and type: netsh wlan show interfaces
 

# Task 2. Use Wi-Fi Access Point
Access the web management interface of a wireless AP or router, e.g., your home wireless router. Explore the settings.
If you do not have access, then try an emulator: TP-Link has web emulators for many devices (https://www.tp-link.com/au/support/emulator/), e.g. under Home -> Routers -> Wireless Routers, try Archer C6 or TL-WR841N.
What are the important settings that you should consider when designing a Wi-Fi network?
In your journal:
• Select the important settings and discuss what you would consider changing them to and why.
• Screenshot/photo of AP settings
 .

