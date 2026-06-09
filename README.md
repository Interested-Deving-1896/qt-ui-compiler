[update-readmes]   Mode: rewrite — migrating to template structure...
# qt-ui-compiler

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/qt-ui-compiler)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/qt-ui-compiler.git
cd qt-ui-compiler
```

## Usage


1. Configure the environment and compilation settings (or use auto-detection).
2. The plugin will monitor files matching the defined pattern.
3. Upon saving a `.ui` file, the corresponding output file is generated or updated.
4. Alternatively, right-click a `.ui` file in the **Project View** or **Editor** and select **Compile UI File**.

### For CLion / C++ Users

If you're using Qt with C++, the plugin will automatically detect the native `uic` executable in your PATH. Make sure Qt's bin directory is in your system PATH, or configure a custom UIC path in the settings.

## Configuration


Settings are located under **Settings/Preferences | Tools | Qt UI Compiler**.

### Environment Settings

- **Virtual Environment Path:** Specify the path to the project's virtual environment (default: `.venv`).
- **Custom UIC Path:** Optional path to a specific `uic` executable if auto-detection is not sufficient.
- **Path Mode:** Toggle whether the paths above are interpreted relative to the project root.

### Compilation Settings

- **Enable auto-compilation:** Globally enable or disable background compilation on save.
- **UI Files Filter:** Use glob patterns (e.g., `**/ui/*.ui`) to define which files the plugin should process (default: `*.ui`).
- **Output Path/Pattern:** Define where the generated files should be stored. Use `$1` as a placeholder for the original filename.

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/qt-ui-compiler`](https://github.com/Interested-Deving-1896/qt-ui-compiler) and mirrored through:

```
Interested-Deving-1896/qt-ui-compiler  ──►  OpenOS-Project-OSP/qt-ui-compiler  ──►  OpenOS-Project-Ecosystem-OOC/qt-ui-compiler
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
<!-- License not detected — add a LICENSE file to this repo. -->
<!-- AI:end:license -->
