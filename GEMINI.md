# Wahoo Results: Patched Fork

## Goal
This fork maintains a patched version of Wahoo Results for the Del Prado Stingrays, enabling features like window resizing on Windows.

## Patches
1. **Window Resizing**: Modified `main_window.py` to set `root.resizable(True, True)` on all platforms.

## Build Process
To build the Windows executable:
1. Push changes to the `build/v1.3.1-patched` branch.
2. GitHub Actions will automatically trigger the `Build Windows Executable` workflow.
3. Download the `wahoo-results.exe` from the workflow artifacts or releases.

## Upstream
- **Project**: https://github.com/JohnStrunk/wahoo-results
- **Base Version**: v1.3.1
