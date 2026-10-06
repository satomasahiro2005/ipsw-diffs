## MobileStoreDemoKit

> `/System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d898` | `0x2db94` | **`+0x2fc`** |
| `__TEXT.__cstring` | `0x7c67` | `0x7d1e` | **`+0xb7`** |
| `__AUTH_CONST.__cfstring` | `0x52c0` | `0x5320` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x2584` | `0x2594` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x398c` | `0x399c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1980` | `0x1988` | **`+0x8`** |

### Other Changes

```diff

-1871.40.52.0.0
+1871.40.61.0.0

-  Functions: 1215
-  Symbols:   1716
-  CStrings:  1255
+  Functions: 1219
+  Symbols:   1719
+  CStrings:  1260
Symbols:
+ -[MSDKManagedDevice isAlwaysRecognizedDemoExperience:]
+ GCC_except_table65
+ GCC_except_table74
+ GCC_except_table84
- GCC_except_table69
CStrings:
+ "%s - result: %d"
+ "-[MSDKManagedDevice isAlwaysRecognizedDemoExperience:]"
+ "/var/mobile/Library/Preferences/com.apple.tvremoted.plist"
+ "AlwaysRecognized"
+ "Invalid value for AlwaysRecognized returned by demod"
```
