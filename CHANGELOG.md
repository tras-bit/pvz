# Changelog

## v0.1.1

- Fixed asset path filtering in `unity/Assets/Editor/PvzImporter.cs` inside
  `unity.zip`: only the `.meta` file suffix is excluded, not asset folders or
  filenames containing `.meta` elsewhere.
- Made root path comparison ordinal and `.meta` suffix detection case-insensitive.

Validation: ZIP integrity and six equivalent path-filter cases checked with Python.
Unity compilation/runtime tests were not run.
