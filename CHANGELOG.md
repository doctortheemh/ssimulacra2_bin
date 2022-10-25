## Version 0.2.1

- Fix compilation with no default features

## Version 0.2.0

- Add support for video comparison
- This change splits ssimulacra2_rs into two subcommands:
  - `ssimulacra2_rs image input.png output.png` for comparing still images. All popular input formats are supported.
  - `ssimulacra2_rs video input.y4m output.y4m` for comparing videos. All popular input formats are supported. This feature requires the `ffmpeg` feature be enabled, which is on by default.