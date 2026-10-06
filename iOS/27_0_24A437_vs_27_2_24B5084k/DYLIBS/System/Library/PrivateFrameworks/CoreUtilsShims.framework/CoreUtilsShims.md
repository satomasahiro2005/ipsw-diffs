## CoreUtilsShims

> `/System/Library/PrivateFrameworks/CoreUtilsShims.framework/CoreUtilsShims`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x189d0` | `0x18eb8` | **`+0x4e8`** |
| `__AUTH_CONST.__auth_got` | `0x728` | `0x758` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xf38` | `0xf68` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x708` | `0x6e0` | **`-0x28`** |
| `__DATA.__data` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__const` | `0x7fa` | `0x80a` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x128` | `0x120` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x3bb` | `0x3b3` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x578` | `0x580` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xc0` | `0xc4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-900.58.0.0.0
+910.21.0.0.0

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 345
-  Symbols:   293
+  Functions: 344
+  Symbols:   297
Symbols:
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_CoreUtilsShims
+ _swift_release_x25
+ _symbolic _____ 8AVFAudio24AVReadOnlyAudioPCMBufferV
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
- _symbolic So16AVAudioPCMBufferC
CStrings:
+ "[%s] ### audio engine start failed: error=%@"
- "[%s] ### audio engine start failed"
```
