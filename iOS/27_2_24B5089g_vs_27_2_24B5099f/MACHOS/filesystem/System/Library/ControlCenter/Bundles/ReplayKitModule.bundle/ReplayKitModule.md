## ReplayKitModule

> `/System/Library/ControlCenter/Bundles/ReplayKitModule.bundle/ReplayKitModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc064` | `0xc0cc` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x660` | `0x680` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2120` | `0x2140` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x309e` | `0x30b9` | **`+0x1b`** |
| `__TEXT.__cstring` | `0x1fcf` | `0x1fe4` | **`+0x15`** |
| `__DATA.__objc_const` | `0x1ef8` | `0x1f08` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xde0` | `0xdf0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xcb8` | `0xcc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x360` | `0x368` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-765.11.1.0.0
+765.14.1.0.0

-  Functions: 244
+  Functions: 245

-  CStrings:  830
+  CStrings:  832
Functions:
~ sub_8588 : 8 -> 92
+ sub_85e4
CStrings:
+ "RPEnableEdgeLightDev"
+ "edgeLightDevOverrideActive"
```
