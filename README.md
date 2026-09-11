# opencode-win32-close-fix

Public fix for opencode win32 `close vs exit` hang (16min scoped never settles).

- `win32-fix.patch`: exit-first plus bounded drain (3 files)
- `.github/workflows/win32-build.yml`: cloud build win32 x64 binary
