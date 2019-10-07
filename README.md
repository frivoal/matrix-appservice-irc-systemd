Get a copy.

`curl -O https://frivoal.github.io/matrix-appservice-irc-systemd/matrix-appservice-irc.service | sudo tee /lib/systemd/system/matrix-appservice-irc.service > /dev/null`

Then modify it to match the location of your config and registration files.

`$EDITOR /lib/systemd/system/matrix-appservice-irc-systemd.service`

Finally, enable and start it.

```
sudo systemctl enable matrix-appservice-irc
sudo systemctl start matrix-appservice-irc
```
