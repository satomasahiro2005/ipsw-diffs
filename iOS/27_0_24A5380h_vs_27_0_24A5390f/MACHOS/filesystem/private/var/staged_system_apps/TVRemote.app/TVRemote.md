## TVRemote

> `/private/var/staged_system_apps/TVRemote.app/TVRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2c81` | `0x2cb1` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x17e0` | `0x1800` | **`+0x20`** |
| `__TEXT.__text` | `0xa760` | `0xa77c` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0xac0` | `0xac8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3f8` | `0x400` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-627.0.14.0.0
+627.0.19.0.0

-  Symbols:   403
-  CStrings:  664
+  Symbols:   404
+  CStrings:  665
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
Functions:
~ sub_100005104 : 8 -> 36
CStrings:
+ "tvrui_migrateAccessibilityPreferencesIfNeeded"
```
