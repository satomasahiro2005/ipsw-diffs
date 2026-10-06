## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/PlugIns/MessageUI.wkbundle/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x7854` | `0x7a63` | **`+0x20f`** |
| `__DATA_CONST.__cfstring` | `0x900` | `0x920` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xbbc` | `0xbdc` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7d2` | `0x7ec` | **`+0x1a`** |
| `__TEXT.__objc_methname` | `0x21e9` | `0x2203` | **`+0x1a`** |
| `__TEXT.__text` | `0x5ef4` | `0x5f08` | **`+0x14`** |
| `__DATA.__objc_const` | `0x1010` | `0x1018` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x830` | `0x838` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 114
+  Functions: 115

-  CStrings:  517
+  CStrings:  518
Functions:
~ sub_4e68 : 208 -> 20
+ sub_4e7c
CStrings:
+ "placeCaretBeforeSignature"
```
