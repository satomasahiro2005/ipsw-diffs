## SAMaintenance

> `/System/Library/ExtensionKit/Extensions/SAMaintenance.appex/SAMaintenance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xd8` | `0xc8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x390` | `0x380` | **`-0x10`** |
| `__TEXT.__cstring` | `0x28` | `0x35` | **`+0xd`** |
| `__DATA_CONST.__auth_got` | `0x1c8` | `0x1c0` | **`-0x8`** |
| `__TEXT.__text` | `0x1770` | `0x176c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.29.1.0.0
+3605.33.1.0.0

-  Symbols:   57
-  CStrings:  6
+  Symbols:   56
+  CStrings:  7
Symbols:
- _swift_bridgeObjectRetain
Functions:
~ sub_100001220 : 132 -> 128
CStrings:
+ "SAMaintenance.Plugin"
+ "com.apple.siri.analytics"
- "com.apple.siri.analytics.SAMaintenance"
```
