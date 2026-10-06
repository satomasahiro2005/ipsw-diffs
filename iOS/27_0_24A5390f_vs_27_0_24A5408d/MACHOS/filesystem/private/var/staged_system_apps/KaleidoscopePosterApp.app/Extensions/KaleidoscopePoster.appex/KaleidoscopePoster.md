## KaleidoscopePoster

> `/private/var/staged_system_apps/KaleidoscopePosterApp.app/Extensions/KaleidoscopePoster.appex/KaleidoscopePoster`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24d54` | `0x24db8` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0x1ee0` | `0x1f40` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x2b79` | `0x2ba9` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xb38` | `0xb50` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x388` | `0x390` | **`+0x8`** |

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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-28.0.0.0.0
+29.0.0.0.0

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  Symbols:   319
-  CStrings:  750
+  Symbols:   320
+  CStrings:  753
Symbols:
+ _OBJC_CLASS_$_CATransaction
Functions:
~ sub_100020eb4 -> sub_100020f0c : 296 -> 336
~ sub_100020fdc -> sub_10002105c : 256 -> 316
CStrings:
+ "begin"
+ "commit"
+ "setDisableActions:"
```
