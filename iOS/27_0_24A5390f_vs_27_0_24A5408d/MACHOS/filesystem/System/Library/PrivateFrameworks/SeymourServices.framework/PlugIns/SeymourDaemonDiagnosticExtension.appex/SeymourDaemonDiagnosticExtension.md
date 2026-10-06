## SeymourDaemonDiagnosticExtension

> `/System/Library/PrivateFrameworks/SeymourServices.framework/PlugIns/SeymourDaemonDiagnosticExtension.appex/SeymourDaemonDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xd4` | `0x107` | **`+0x33`** |
| `__DATA_CONST.__cfstring` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__text` | `0x168` | `0x188` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.0.134.0.0
+2027.0.146.0.2

-  Symbols:   23
-  CStrings:  16
+  Symbols:   24
+  CStrings:  17
Symbols:
+ _objc_release_x22
+ _objc_release_x24
- _objc_release_x23
Functions:
~ sub_100000a24 : 348 -> 380
CStrings:
+ "/var/mobile/Library/Seymour/seymour_catalog.sqlite"
```
