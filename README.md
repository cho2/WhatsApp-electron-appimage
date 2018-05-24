# WhatsApp - Electron version

This thing won't work if you're not connected to the internet.

Requires `npm`.

To build and install, run:

```
npm install && npm run package-linux
sudo cp -r release-builds/WhatsApp-linux-x64 /opt/ && sudo ln -s /opt/WhatsApp-linux-x64/WhatsApp /usr/local/bin/WhatsApp
sudo desktop-file-install WhatsApp.desktop
sudo install -D assets/icons/png/16x16.png /usr/local/share/icons/hicolor/16x16/apps/WhatsApp.png
sudo install -D assets/icons/png/32x32.png /usr/local/share/icons/hicolor/32x32/apps/WhatsApp.png
sudo install -D assets/icons/png/64x64.png /usr/local/share/icons/hicolor/64x64/apps/WhatsApp.png
sudo install -D assets/icons/png/128x128.png /usr/local/share/icons/hicolor/128x128/apps/WhatsApp.png
sudo install -D assets/icons/png/256x256.png /usr/local/share/icons/hicolor/256x256/apps/WhatsApp.png
sudo install -D assets/icons/png/512x512.png /usr/local/share/icons/hicolor/512x512/apps/WhatsApp.png
sudo install -D assets/icons/png/1024x1024.png /usr/local/share/icons/hicolor/1024x1024/apps/WhatsApp.png
```

To uninstall, run:

```
sudo rm -r /opt/WhatsApp-linux-x64 \
/usr/local/bin/WhatsApp \
/usr/local/share/applications/WhatsApp.Desktop \
/usr/local/share/icons/hicolor/16x16/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/32x32/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/64x64/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/128x128/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/256x256/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/512x512/apps/WhatsApp.png \
/usr/local/share/icons/hicolor/1024x1024/apps/WhatsApp.png
```
