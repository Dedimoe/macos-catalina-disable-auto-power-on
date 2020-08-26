# macos-catalina-disable-auto-power-on
Mac OS Catalina: how to disable auto-power-on when open up

Open terminal with: press Command - spacebar to launch Spotlight and type "Terminal", then double-click the search result. You'll see a small window with a white background open on your desktop, and then type the following:
```
sudo nvram AutoBoot=%00
```
Then enter your password.

To reset your Mac to its default behavior (auto power on), type the following:
```
sudo nvram AutoBoot=%03
```
Just it.
