# duckdb-windows-extensions
DuckDB extensions for Windows users working behind a corporate firewall who cannot simply `INSTALL extension;` within the `duckdb` CLI.

1. Download the archive from the release section.
2. Extract the files and place them in `~/.duckdb/extensions/v0.8.1/windows_amd64`
3. Load extensions within the `duckdb` CLI, e.g. `LOAD spatial;`.


