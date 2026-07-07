# Reclaimed Design Systems

Design systems developed during the AAVS26 Reclaim Seoul Workshop.

This repository collects reusable aggregation/design systems for material reuse workflows. Each system is stored as a folder inside `systems/`, with its own metadata, aggregation data, thumbnail, and generated documentation.

## Available systems

<!-- CATALOG:START -->
<!-- This section is automatically generated. Do not edit manually. -->

| Preview | System |
|---|---|
| ![Multi-Bottle System](systems/bottles-system/00_thumb.png) | [Multi-Bottle System](systems/bottles-system/)<br><br>A system for reusing bottles with different sizes<br><br>by Andrea Rossi<br>[aggregation.json](systems/bottles-system/aggregation.json) · [meta.json](systems/bottles-system/meta.json) |
| ![melted plastic](systems/melted-plastic/00_thumb.jpg) | [melted plastic](systems/melted-plastic/)<br><br>A system for reusing bottles with different sizes<br><br>by SEUNGCHAN BAEK, JIHYEON BAEK<br>[aggregation.json](systems/melted-plastic/aggregation.json) · [meta.json](systems/melted-plastic/meta.json) |
| ![plastic bottles with multi degree](systems/plasticbottles/00_thumb.jpg) | [plastic bottles with multi degree](systems/plasticbottles/)<br><br>A system for reusing bottles with different sizes<br><br>by Seunghyuk Hyun, Han<br>[aggregation.json](systems/plasticbottles/aggregation.json) · [meta.json](systems/plasticbottles/meta.json) |
| ![Test system](systems/test-system/00_thumb.png) | [Test system](systems/test-system/)<br><br>A system for reusing bottles with different sizes<br><br>by Andrea Rossi<br>[aggregation.json](systems/test-system/aggregation.json) · [meta.json](systems/test-system/meta.json) |
| ![tree-angle](systems/tree-angle/00_thumb.png) | [tree-angle](systems/tree-angle/)<br><br>A system for reusing wood with different sizes<br><br>by tree-team<br>[aggregation.json](systems/tree-angle/aggregation.json) · [meta.json](systems/tree-angle/meta.json) |
| ![Multi-Bottle System](systems/useatlas/00_thumb.png) | [Multi-Bottle System](systems/useatlas/)<br><br>A system for reusing bottles with different sizes<br><br>by Andrea Rossi<br>[aggregation.json](systems/useatlas/aggregation.json) · [meta.json](systems/useatlas/meta.json) |

<!-- CATALOG:END -->

## Repository structure

```txt
systems/
  <system-slug>/
    aggregation.json
    meta.json
    00_thumb.png
    README.md

catalog/
  catalog.json

scripts/
  build_catalog.mjs
