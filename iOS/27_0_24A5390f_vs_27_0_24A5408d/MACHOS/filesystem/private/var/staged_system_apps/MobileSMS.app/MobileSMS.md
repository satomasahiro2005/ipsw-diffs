## MobileSMS

> `/private/var/staged_system_apps/MobileSMS.app/MobileSMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6ac` | `0x1c6e0` | **`+0x34`** |
| `__TEXT.__objc_stubs` | `0x3f60` | `0x3f80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4eec` | `0x4f04` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1548` | `0x1550` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1487.100.6.2.2
+1491.100.1.2.11

-  CStrings:  1319
+  CStrings:  1320
Symbols:
+ _OBJC_CLASS_$_CKMEPFeatures
- _OBJC_CLASS_$_IMSWHighlightCenterController
Functions:
~ sub_100001da0 : 668 -> 640
~ sub_100002634 -> sub_100002618 : 2592 -> 2628
~ sub_10000312c -> sub_100003134 : 152 -> 196
CStrings:
+ "sharedFeatures"
+ "shouldStartPerfTestWithoutOrientationChange"
- "sharedControllerWithAppIdentifier:"
```
