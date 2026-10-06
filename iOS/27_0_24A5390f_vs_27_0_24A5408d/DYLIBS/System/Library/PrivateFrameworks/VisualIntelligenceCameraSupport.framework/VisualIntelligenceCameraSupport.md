## VisualIntelligenceCameraSupport

> `/System/Library/PrivateFrameworks/VisualIntelligenceCameraSupport.framework/VisualIntelligenceCameraSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39ee0` | `0x3a870` | **`+0x990`** |
| `__TEXT.__eh_frame` | `0x19d8` | `0x1a58` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xca5` | `0xd25` | **`+0x80`** |
| `__TEXT.__cstring` | `0x689` | `0x6d4` | **`+0x4b`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xeb8` | **`+0x38`** |
| `__TEXT.__const` | `0x304c` | `0x307c` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xbf4` | `0xc24` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xb90` | `0xbb0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xde0` | `0xdf0` | **`+0x10`** |
| `__AUTH.__data` | `0xa30` | `0xa38` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0x1bf8` | `0x1c00` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xac` | `0xb0` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x7c` | `0x80` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-234.0.0.0.0
+246.0.0.0.0

-  Functions: 1192
-  Symbols:   608
-  CStrings:  98
+  Functions: 1201
+  Symbols:   607
+  CStrings:  104
Symbols:
+ ___swift_memcpy96_8
- ___swift_memcpy73_8
- _objc_retain_x27
CStrings:
+ "autoResume"
+ "awaitCaptureEffectsMedia()"
+ "configUpdate"
+ "layoutChange"
+ "rebuildSession(%{public}s): invalidating old session contexts"
+ "resume"
+ "trackerChange"
- "rebuildSession() called — invalidating old session contexts"
```
