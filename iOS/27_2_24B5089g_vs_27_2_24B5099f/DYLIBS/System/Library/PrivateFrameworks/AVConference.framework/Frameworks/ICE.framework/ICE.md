## ICE

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d964` | `0x2db10` | **`+0x1ac`** |
| `__DATA.__data` | `0x128` | `0x4` | **`-0x124`** |
| `__DATA_DIRTY.__data` | `0x4` | `0x128` | **`+0x124`** |
| `__TEXT.__oslogstring` | `0xc37a` | `0xc445` | **`+0xcb`** |
| `__TEXT.__unwind_info` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1777` | `0x1779` | **`+0x2`** |

### Other Changes

```diff

-2260.11.1.0.0
+2260.14.1.0.0

-  Functions: 529
-  Symbols:   479
-  CStrings:  775
+  Functions: 532
+  Symbols:   480
+  CStrings:  776
Symbols:
+ _NormalizeCandidateInterfaceNames
CStrings:
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/ICE.subproj/Sources/ICE.c:%d: NormalizeCandidateInterfaceNames failed (%08X)"
+ "%%%.*s"
- "%%%s"
```
