# RKP project for Windows


1. Download Shadowsocks client:
	- Tested on 4.4.0: https://github.com/shadowsocks/shadowsocks-windows/releases/download/4.4.0.0/Shadowsocks-4.4.0.185.zip
	- >*Newest release just in case: https://github.com/shadowsocks/shadowsocks-windows/releases*

2. Replace *gui-config.json* and *pac.txt* files in Shadowsocks folder

3. Run Shadowsocks.exe

4. Copy "ss://..." server access string to clipboard
	- To get it, contact your local JVD agent

5. Rightclick on the Shadowsocks tray icon, choose "Серверы > Импорт адреса из буфера обмена... > [OK] > [ОК] > [ОК]"

6. ???

7. q==[\*><\*]===b

---

If your Chrome browser cannot pick up system proxy settings:

1. Make sure you disable all VPN/proxy extensions.

2. Right-click Chrome shortcut, Click Properties, Add this line after chrome.exe with a space: `--proxy-server="socks5://127.0.0.1:1080" `
	
	eg: `E:\Chrome\chrome.exe --proxy-server="socks5://127.0.0.1:1080"`

---
