# CADO device overlay

Authoritative source for the 6 CADO device configs that this fork
(`dryob/tuya-local`) adds on top of upstream `make-all/tuya-local`.

The `sync-upstream.yml` workflow rebuilds `main` from upstream each day
and re-applies these files via `devices/`. Edit CADO configs HERE, not on
`main` (main is overwritten by the sync job).

Files map to `custom_components/tuya_local/devices/` on `main`.
