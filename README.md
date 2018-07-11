# glTF-Generator-Registry
An open registry of tools that create glTF assets.

## Fields

| field | required | description |
|---|---|---|
| generator | ✅ | Exact `asset.generator` ID string used in glTF assets. Globs (`*`) may be used in place of version strings. |
| name | ✅ | Human-friendly name of the generator. Names are _not_ guaranteed to be unique. For example, "Blender exporter" is a reasonable name, but must be shown with the `author` field to be unique. |
| author | ✅ | Author of the generator. |
| docsURL | ✅ | URL for homepage or documentation. |
| bugsURL | | URL for reporting issues. |
| bugsText | | If no URL is available, instructions for reporting issues may be given here. |
| type | ✅ | `EXPORTER` or `CONVERTER` |
