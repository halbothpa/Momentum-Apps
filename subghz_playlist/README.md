# SubGHz Playlist Stub

This is a minimal stub implementation required for the Momentum firmware build process.

## Purpose

The Momentum firmware's archive application (`applications/main/archive/helpers/archive_files.c`) includes a dependency on `subghz_playlist/playlist_file.h`. This stub provides the minimal header and implementation needed to satisfy that dependency while keeping this repository focused on the proto_pirate FAP.

## Contents

- `playlist_file.h` - Header file with function declaration
- `playlist_file.c` - Stub implementation that returns 0
- `application.fam` - Minimal FAP definition for build system

The actual subghz_playlist functionality is not included - this is only a build compatibility stub.
