## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2d0c` | `0xe2d8c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x20da0` | `0x20dc0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x54ee` | `0x550e` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xed8` | `0xee0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf18` | `0xaf20` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1070.61.0.0.0
+1070.62.0.0.0

-  Symbols:   11985
-  CStrings:  5320
+  Symbols:   11986
+  CStrings:  5322
Symbols:
+ _MGGetStringAnswer
Functions:
~ -[WiFiDiagnosticReporter initABCReporter] : 96 -> 224
CStrings:
+ "%s: Set WiFi chipset for ABC: %@"
+ "WifiChipset"
```
