## OBCEngagePlugin

> `/System/Library/ExtensionKit/Extensions/OBCEngagePlugin.appex/OBCEngagePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11b74` | `0x11a6c` | **`-0x108`** |
| `__TEXT.__eh_frame` | `0x980` | `0x9f8` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x621` | `0x5d1` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x440` | `0x458` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xe80` | `0xe90` | **`+0x10`** |
| `__TEXT.__const` | `0xc98` | `0xca8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x138` | `0x143` | **`+0xb`** |
| `__DATA_CONST.__auth_got` | `0x748` | `0x750` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x278` | `0x27e` | **`+0x6`** |
| `__TEXT.__swift5_reflstr` | `0x440` | `0x43c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  Functions: 298
-  Symbols:   133
+  Functions: 300
+  Symbols:   134
Symbols:
+ _swift_retain_x25
CStrings:
+ "preference"
- "Failed to decode OBCEngageCustomTaskParameters from PluginPreference: %@"
```
