# ilyamen's DMS plugins

A plugin registry for [DankMaterialShell](https://github.com/AvengeMedia/DankMaterialShell).

## Usage

In DMS Settings → Plugins → Registries, add:

```
https://github.com/ilyamen/dms-plugin-registry.git
```

The plugins then show up in Browse next to the official ones.

## Plugins

| Plugin | Description |
| --- | --- |
| [Bluetooth Address](https://github.com/ilyamen/dms-bt-address) | Give the Bluetooth adapter an address of your choice and keep it, so a dual-boot system stops losing pairings to the other OS |

## Adding a plugin

Add `plugins/<author>-<plugin-name>.json` in the format of the [official registry](https://github.com/AvengeMedia/dms-plugin-registry/blob/master/CONTRIBUTING.md). `id` and `name` must match the plugin's `plugin.json`.
