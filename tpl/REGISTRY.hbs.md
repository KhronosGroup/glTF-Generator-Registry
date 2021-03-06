# glTF-Generator-Registry v{{ version }}

This registry should not be considered an exhaustive list of glTF creation
tools, but rather a highly-structured collection of metadata for a subset of
existing tools. Editors and viewers that load glTF files may use this registry
to help their users report bugs appropriately when glTF files contain errors.

<!--

  **NOTICE:** This file is generated automatically from `registry.json`.
  Please do not edit this file directly.

-->

| name | author | generator ID | type | docsURL | bugsURL | bugsText |
|-----------|------|--------|------|---------|---------|----------|
{{#each generators}}| **{{ name }}** | {{ author }} | {{ generator }} | `{{ type }}` | {{#if docsURL}}[docs]({{ docsURL }}){{/if}} | {{#if bugsURL}}[bugs]({{ bugsURL }}){{/if}} | {{ bugsText }} |
{{/each}}
