# http-to-https

[![Snap Status](https://build.snapcraft.io/badge/roshub/http-to-https.svg)](https://build.snapcraft.io/user/roshub/http-to-https)

An http to https redirect microservice.

## Install


[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/http-to-https)

```
snap install http-to-https
```

## Configuration

This snap has one parameter, `port` which defaults to `8000`. Use the `snap set` command to update the port. Changes take effect immediately if the service is running.


```
snap set http-to-https port=80
```


```
snap get http-to-https port=80
```

## Logging

View logs using `snap logs`

```
snap logs -f http-to-https
```


# Credits

[<img src=./icons/roshub_logo_cropped_large.png width=300>](https://roshub.io)

http-to-https is open source software developed by [RosHub Inc.](https://roshub.io)