## Vermillion

> `/System/Library/ExtensionKit/Extensions/Vermillion.appex/Vermillion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a40` | `0x10b18` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x1aa` | `0x15a` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0xfb0` | `0xff0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xcb0` | `0xcf0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x7e0` | `0x800` | **`+0x20`** |
| `__TEXT.__const` | `0xea0` | `0xe92` | **`-0xe`** |
| `__TEXT.__objc_methname` | `0x284` | `0x28f` | **`+0xb`** |
| `__DATA_CONST.__auth_ptr` | `0x358` | `0x360` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x4f8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x379` | `0x37f` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  Functions: 317
-  Symbols:   143
+  Functions: 319
+  Symbols:   144
Symbols:
+ _swift_retain_x25
CStrings:
+ "preference"
- "Failed to decode VermillionTaskPreference from PluginPreference: %@"
```
