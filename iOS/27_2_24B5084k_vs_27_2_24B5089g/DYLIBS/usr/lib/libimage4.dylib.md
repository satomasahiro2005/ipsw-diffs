## libimage4.dylib

> `/usr/lib/libimage4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x3b8` | `0x590` | **`+0x1d8`** |
| `__AUTH.__data` | `0x120` | `—` | **`-0x120`** |
| `__DATA.__data` | `0xb8` | `—` | **`-0xb8`** |
| `__TEXT.__text` | `0x2bc28` | `0x2bc38` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _X509ExtensionParseBasicConstraints : 208 -> 212
~ _X509ChainBuildPathPartial : 488 -> 500
CStrings:
+ "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Sun Sep 13 19:56:21 PDT 2026; root:AppleImage4_libraries-374~8937/libimage4/RELEASE_ARM64E"
+ "Darwin Image4 Library Version 7.0.0: Sun Sep 13 19:56:21 PDT 2026; root:AppleImage4_libraries-374~8937/libimage4/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Fri Sep  4 20:21:50 PDT 2026; root:AppleImage4_libraries-374~8668/libimage4/RELEASE_ARM64E"
- "Darwin Image4 Library Version 7.0.0: Fri Sep  4 20:21:50 PDT 2026; root:AppleImage4_libraries-374~8668/libimage4/RELEASE_ARM64E"
```
