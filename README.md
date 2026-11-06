# YubiStop 🛑

Stop poping your YubiKey on Mattermost !

# Install as a `systemd` service

```
sudo install -Dm644 yubistop.bt /usr/local/share/yubistop/yubistop.bt
sudo install -Dm644 yubistop.service /etc/systemd/system/yubistop.service
sudo systemctl daemon-reload
sudo systemctl enable --now yubistop
journalctl -u yubistop -f
```
