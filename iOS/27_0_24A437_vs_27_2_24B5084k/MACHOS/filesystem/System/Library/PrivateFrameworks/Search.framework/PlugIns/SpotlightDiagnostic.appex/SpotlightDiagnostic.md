## SpotlightDiagnostic

> `/System/Library/PrivateFrameworks/Search.framework/PlugIns/SpotlightDiagnostic.appex/SpotlightDiagnostic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eec` | `0x2028` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x476` | `0x4d3` | **`+0x5d`** |
| `__DATA_CONST.__cfstring` | `0x420` | `0x440` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x204` | `0x21c` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x3f0` | `0x3e0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x208` | `0x200` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2459.105.0.0.0
+2465.1.2.0.0

-  Symbols:   99
-  CStrings:  148
+  Symbols:   98
+  CStrings:  149
Symbols:
- _objc_retain_x26
Functions:
~ sub_100000d70 : 708 -> 740
~ sub_100001034 -> sub_100001054 : 4232 -> 4516
CStrings:
+ "^(build-history|CoreSpotlight-heartbeat|Spotlight_\\d{4}-\\d{2}-\\d{2}-\\d{2}-\\d{2}-\\d{2})\\.log$"
```
