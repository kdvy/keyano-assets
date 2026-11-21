# Keyano assets

Large files for the Keyano app. They are release assets, not files in the
git history. The Keyano build downloads them and checks their checksums.

## Piano sample set

- Release tag: `piano-kw-20220221`
- Asset: `UprightPianoKW-20220221.sf2` (57 MB)
- SHA-256: `d9f5157720963671906727ca2e12b3293fd822c831bb0de477dd1c5f3ad37108`
- Name: Upright Piano KW, version 2022-02-21, SF2 format
- Authors: Gonzalo and Roberto, FreePats project
- Source: https://freepats.zenvoid.org/Piano/acoustic-grand-piano.html
- Licence: Creative Commons CC0 1.0 public domain dedication,
  https://creativecommons.org/publicdomain/zero/1.0/

The workflow `.github/workflows/release-piano.yml` downloads the archive from
FreePats, checks the checksums, and creates the release.
