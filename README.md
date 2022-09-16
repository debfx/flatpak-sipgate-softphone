# Flatpak for sipgate Softphone

## Install

```
flatpak install flathub org.freedesktop.Sdk//22.08
flatpak install flathub org.electronjs.Electron2.BaseApp//22.08
flatpak-builder --user --install --force-clean build-dir de.sipgate.softphone.yaml
```

## Check latest version

Version information: https://sipgate-desktop-app.s3.eu-central-1.amazonaws.com/latest-linux.yml
