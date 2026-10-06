## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/DiagnosticExtensionsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75d0c` | `0x75f8c` | **`+0x280`** |
| `__AUTH_CONST.__objc_const` | `0x13aa0` | `0x13b30` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x700c` | `0x7054` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b98` | `0x3bc8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x98e8` | `0x9908` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5700` | `0x56f0` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x5e8` | `0x5f4` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x2180` | `0x2188` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1cd0` | `0x1cc8` | **`-0x8`** |

### Other Changes

```diff

-223.0.0.0.0
+224.0.0.0.0

-  Functions: 2926
-  Symbols:   4287
-  CStrings:  1790
+  Functions: 2932
+  Symbols:   4297
+  CStrings:  1791
Symbols:
+ -[DEDBugSessionConfiguration seedingCookieName]
+ -[DEDBugSessionConfiguration seedingFilerURL]
+ -[DEDBugSessionConfiguration seedingUsesPinning]
+ -[DEDBugSessionConfiguration setSeedingCookieName:]
+ -[DEDBugSessionConfiguration setSeedingFilerURL:]
+ -[DEDBugSessionConfiguration setSeedingUsesPinning:]
+ _DEDKeySeedingCookieName
+ _DEDKeySeedingFilerURL
+ _DEDKeySeedingUsesPinning
+ _OBJC_IVAR_$_DEDBugSessionConfiguration._seedingCookieName
+ _OBJC_IVAR_$_DEDBugSessionConfiguration._seedingFilerURL
+ _OBJC_IVAR_$_DEDBugSessionConfiguration._seedingUsesPinning
- _DEDKeySeedingEnvironment
- _DEDSeedingClientFilerURL
CStrings:
+ "Discovery returned [%lu] extensions"
+ "No cached extensions; re-running discovery"
+ "Pinning disabled by config; skipping pinning check."
+ "seedingCookieName"
+ "seedingFilerURL"
+ "seedingUsesPinning"
- "FBAFilerURL"
- "Running in development mode; skipping pinning check."
- "Using user default value for filer URL"
- "_seedportal_session_uat"
- "seedingEnvironment"
```
