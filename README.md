# sandisk-media-drive-32gb-mods

This repo provides information and modifications for the Sandisk Media Drive 32gb

The root password for the device is `sqn1351`. It is believed that this is the same across all devices. This should be changed immediately.

To change the root password you can do this via `telnet`.

## Login with root 

```telnet <MEDIA DRIVE IP>```

## Change password

```passwd```

## Disable Anonymous FTP

The file in `files/etc/rc.d/init.d/service` provides the necessary addtion of the `-E` flag for pureFTP. Now that you have root access you can simply copy this to the media drive by logging into FTP using the root user.

### More details coming soon...
