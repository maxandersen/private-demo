# Quarkus Home Assistant DevService image

This builds an image that runs Home Assistant to use in a Quarkus dev mode.

For now it is hardwired to enable the [demo](https://www.home-assistant.io/integrations/demo/) integrations.

Currently it has a fixed user/name password and token defined - not to be used in production!

If you know of a better way to do this, please let me know in this post at [Home Assistant forum](https://community.home-assistant.io/t/setup-homeassistant-automagically-for-testing/707480).

## Info

username: `admin`
password: `secret`
token: `eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiI0MzhjOTcwNTVmNjk0NWFmYjBhMjUxM2YzOTRjNmU0NiIsImlhdCI6MTcxMTMxMjE1MiwiZXhwIjoyMDI2NjcyMTUyfQ.cCKzD6ZiGjv-jFR8iy7MxpozBA-vEMYqShv-bh81CiM`