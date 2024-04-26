# nemo-nextcloud

Adds Nextcloud integration to the [Nemo](https://github.com/linuxmint/nemo) file
manager.

Adapted from the Nautilus ownCloud plugin by Klaas Freitag (fork of [nemo-owncloud](https://github.com/spinda/nemo-owncloud)).

Requires
[`nextcloud-client`](https://github.com/nextcloud/desktop)
and
[`nemo-python`](https://github.com/linuxmint/nemo-extensions/tree/master/nemo-python).

## Usage

Install `usr/share/nemo-python/extensions/syncstate.py` to the corresponding
directory on your system.

Make sure the Nextcloud client is running, then run `nemo -q` to close any
running Nemo instances and load the plugin.

The Nextcloud client must be running before Nemo opens, or the plugin will fail
to load.

## License

GPLv2 or later (see
[`syncstate.py`](usr/share/nemo-python/extensions/syncstate.py))
