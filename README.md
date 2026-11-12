# Pengroove plugins

Public information that every copy of Pengroove Admin reads, with no sign-in or token:

- `admin.json`: the latest admin version, what each release brings, and how to update.
  Settings → Updates in each admin reads it from
  `https://raw.githubusercontent.com/ajokhai/pengroove-plugins/main/admin.json`.

- `plugins.json`: every plugin, with what it does, what you get, its version and what's new.
  The Plugins page in each admin (1.52.0 and later) reads it from
  `https://raw.githubusercontent.com/ajokhai/pengroove-plugins/main/plugins.json`, to show plugins a site
  doesn't have yet and newer versions of ones it has.

Next: the plugins' own code moves here, so each site downloads only the plugins it uses.
