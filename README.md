# character-sheets
An omnibus of personal RPG characters, active and stale.

## High Level Objectives

1. Edit in plain text, not PDFs
2. Keep layouts flexible and multiplatform
3. Make it easy to version and share characters and stories

## Folder Structure

1. System (dnd5e)
    a. Character (hawkeye)
        i. metadata.yaml
        ii. hawkeye.md
2. System (dungeon-world)
3. etc.

## Intended Flow

* Numerics in `metadata.yaml`
* Markdown with most text and high level layout in `character.md`
* Pandoc interpolates character with metadata for simple output
* Optional files can be referenced for templating for HTML or PDF publishing
    * Considering Brewmastery css standalone to do HTML templating
    * Will need TeX shell for PDFs
