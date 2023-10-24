### Init file

The init file helps you run pre-setup commands and avoid credential leak.

### Usage

If you want to explicitly run it via CLI:
```
duckdb -init duckdbrc
```

You can also make the file a `.duckdbrc` and it will run automatically as soon as you run the duckdb in the CLI.