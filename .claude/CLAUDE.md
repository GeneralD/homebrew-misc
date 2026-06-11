# homebrew-misc

Personal Homebrew tap (GeneralD/misc) holding 16 macOS cask definitions for
apps not in the official `homebrew/cask` repo (VRoid Studio, KensingtonWorks,
Stability Matrix, Unity helper tools, XM MT4/MT5, etc.).

- Stack: Ruby (Homebrew cask DSL), one file per cask under `Casks/`
- Status: active personal tap; casks migrated from a private tap (2026-03)
- Most casks use `sha256 :no_check` due to unversioned upstream URLs
- No build step. Verify a cask locally with:
  `brew install --cask <path-to-rb>` or `brew audit --cask Casks/<name>.rb`
- Usage: `brew tap GeneralD/misc && brew install --cask <name>`
- No LICENSE file, no CI.
