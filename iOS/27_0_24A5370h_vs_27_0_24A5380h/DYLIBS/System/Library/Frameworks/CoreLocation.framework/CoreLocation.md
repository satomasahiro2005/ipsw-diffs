## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x204210` | `0x204088` | **`-0x188`** |
| `__AUTH.__objc_data` | `0x2850` | `0x2800` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5a0` | `0x5f0` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x10228` | `0x10258` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xb680` | `0xb6a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x24770` | `0x24781` | **`+0x11`** |
| `__TEXT.__const` | `0x4c60` | `0x4c50` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0xf1b8` | `0xf1a8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x9afc` | `0x9b0c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5610` | `0x5620` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xda8` | `0xdb0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x688` | `0x690` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5258` | `0x5260` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xaf8` | `0xafc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3169.4.0.0.0
+3176.0.0.0.0

-  Functions: 5176
-  Symbols:   1081
-  CStrings:  5500
+  Functions: 5178
+  Symbols:   1082
+  CStrings:  5501
Symbols:
+ _objc_release_x28
CStrings:
+ "22:02:43"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 242,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 243,invalid element %zu <= %zu."
+ "Jun 27 2026"
+ "startsNewSegment"
- "00:15:46"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 240,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 241,invalid element %zu <= %zu."
- "Jun 16 2026"
```
