
### Enabling / Disabling Lock Screen in Ubuntu



*To diable lock screen:*
```
gsettings set org.gnome.desktop.lockdown disable-lock-screen 'true'

```
*To enable back:*
```
gsettings set org.gnome.desktop.lockdown disable-lock-screen 'false'
```

*To view the current setting:*
```
gsettings get org.gnome.desktop.lockdown disable-lock-screen
```

Reference: https://askubuntu.com/questions/1048774/disabling-lock-screen-18-04

