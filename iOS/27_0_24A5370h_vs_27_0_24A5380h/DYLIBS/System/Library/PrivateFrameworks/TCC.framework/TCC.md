## TCC

> `/System/Library/PrivateFrameworks/TCC.framework/TCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15a84` | `0x15c28` | **`+0x1a4`** |
| `__TEXT.__oslogstring` | `0x1559` | `0x1665` | **`+0x10c`** |
| `__DATA_CONST.__const` | `0x18d0` | `0x1870` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x2d0` | **`-0x50`** |
| `__TEXT.__cstring` | `0x336e` | `0x3383` | **`+0x15`** |
| `__TEXT.__unwind_info` | `0x610` | `0x618` | **`+0x8`** |

### Other Changes

```diff

-906.0.0.0.0
+909.0.0.0.0

-  Functions: 594
-  Symbols:   957
-  CStrings:  605
+  Functions: 598
+  Symbols:   962
+  CStrings:  610
Symbols:
+ _CFPropertyListCreateWithStream
+ _CFReadStreamClose
+ _CFReadStreamCreateWithFile
+ _CFReadStreamOpen
+ _CFURLCreateFromFileSystemRepresentation
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_11
- ___TCCAccessCheckIfDisclosurePromptIsNeeded_block_invoke
- ___TCCAccessCheckIfDisclosurePromptIsNeeded_block_invoke_2
CStrings:
+ "%{public}s for bundleID: %s URL for cache: %s"
+ "%{public}s for bundleID: %s URL is empty)"
+ "%{public}s for bundleID: %s Unable to create read stream for URL: %s"
+ "%{public}s for bundleID: %s Unable to create stream for URL: %s"
+ "%{public}s: %s needs prompt for disclosure: %d"
+ "%{public}s: plist decode failed (bundleID: %s)"
+ "/private/var/mobile/Library/ManagedAppPrivacy/managed_disclosure_cache.plist"
- "TCCAccessCheckIfDisclosurePromptIsNeeded() IPC"
- "TCCAccessCheckIfDisclosurePromptIsNeeded_block_invoke_2"
```
