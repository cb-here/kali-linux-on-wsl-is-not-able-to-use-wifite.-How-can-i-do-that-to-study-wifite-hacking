# kali-linux-on-wsl-is-not-able-to-use-wifite.-How-can-i-do-that-to-study-wifite-hacking
wifite not working in wsl
# kali-linux-on-wsl-is-not-able-to-use-wifite.-How-can-i-do-that-to-study-wifite-hacking

wifite not working in wsl


┏━(Message from Kali developers)
┃
┃ This is a minimal installation of Kali Linux, you likely
┃ want to install supplementary tools. Learn how:
┃ ⇒ https://www.kali.org/docs/troubleshooting/common-minimum-setup/
┃
┗━(Run: “touch ~/.hushlogin” to hide this message)
┌──(kali㉿CB-here)-[~]
└─$ sudo wifite
[sudo] password for kali:
   .               .
 .´  ·  .     .  ·  `.  wifite2 2.7.0  :  :  :  (¯)  :  :  :  a wireless auditor by derv82  `.  ·  `/¯\ ´  ·  .´  maintained by kimocoder   `     /¯¯¯\     ´    https://github.com/kimocoder/wifite2

 [!] Warning: Recommended app bully was not found. install @ https://github.com/kimocoder/bully
 [!] Warning: Recommended app hashcat was not found. install @ https://hashcat.net/hashcat/
 [!] Warning: Recommended app hcxdumptool was not found. install @ apt install hcxdumptool
 [!] Warning: Recommended app hcxpcapngtool was not found. install @ apt install hcxtools
 [!] Warning: Recommended app macchanger was not found. install @ apt install macchanger

 [+] Checking airmon-ng...
 [!] airmon-ng did not find any wireless interfaces
 [!] Make sure your wireless device is connected
 [!] See https://www.aircrack-ng.org/doku.php?id=airmon-ng for more info

 [!] Error: airmon-ng did not find any wireless interfaces

 [!] Full stack trace below

 [!]    Traceback (most recent call last):
 [!]    File "/usr/lib/python3/dist-packages/wifite/__main__.py", line 104, in entry_point
 [!]        wifite.start()
 [!]    File "/usr/lib/python3/dist-packages/wifite/__main__.py", line 57, in start
 [!]        Configuration.get_monitor_mode_interface()
 [!]    File "/usr/lib/python3/dist-packages/wifite/config.py", line 229, in get_monitor_mode_interface
 [!]        cls.interface = Airmon.ask()
 [!]                        ^^^^^^^^^^^^
 [!]    File "/usr/lib/python3/dist-packages/wifite/tools/airmon.py", line 313, in ask
 [!]        raise Exception('airmon-ng did not find any wireless interfaces')
 [!]  Exception: airmon-ng did not find any wireless interfaces

 [!] Exiting
