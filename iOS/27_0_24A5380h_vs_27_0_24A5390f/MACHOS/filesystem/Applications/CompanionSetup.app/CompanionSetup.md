## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa016c` | `0xa03b4` | **`+0x248`** |
| `__TEXT.__objc_stubs` | `0x2920` | `0x2960` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1553` | `0x1583` | **`+0x30`** |
| `__DATA.__data` | `0x2160` | `0x2180` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1208` | `0x1218` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x27a0` | `0x27b0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4c0d` | `0x4c1d` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f70` | `0x1f80` | **`+0x10`** |
| `__DATA.__objc_data` | `0x1fe8` | `0x1ff0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x13d8` | `0x13e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd70` | `0xd78` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x17c8` | `0x17d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-524.0.26.0.0
+524.0.38.0.0

-  Functions: 2446
-  Symbols:   1259
-  CStrings:  1402
+  Functions: 2448
+  Symbols:   1261
+  CStrings:  1405
Symbols:
+ _OBJC_CLASS_$_UIKeyboardImpl
+ _UIKeyboardAutomaticIsOnScreen
CStrings:
+ "Forcing software keyboard on screen."
+ "activeInstance"
+ "ejectKeyDown"
```
