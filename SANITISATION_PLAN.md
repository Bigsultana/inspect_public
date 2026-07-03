# Sanitisation Plan

Goal: create a neutral public version of the private inspection app without exposing company names, client names, project names, templates, private documentation, or trial data.

## Remove or neutralise

- Company names and footer labels.
- Named clients.
- Named inspectors.
- Project IDs and project names.
- Trial fill data.
- Private report templates.
- Internal review notes.
- Private release folders.
- Private vendor paths or local machine paths.
- Any references to non-public business relationships.

## Keep functionality

- Inspection metadata.
- Inspection type selector.
- Wall type selector.
- Footing subtype selector.
- Temporary stability fields.
- Retaining wall fields.
- Masonry-faced reinforced earth Form A and Form B sections.
- Yes / no / not applicable dropdowns.
- Photo picker and camera workflow.
- Immediate photo thumbnails.
- Saved records stored in local browser storage.
- JSON export.
- Optional GPS capture if enabled later.

## Public app target

Use neutral names only:

- App name: Site Inspect.
- Storage key prefix: site_inspect.
- Export file prefix: site_inspect.
- Default Project ID: PRJ-001.
- Default inspector: blank.

## Implementation note

The GitHub connector currently blocks large HTML and JavaScript replacements. Manual paste through the GitHub web editor may be required for the full public app file until the project is split into source files with a build process.
