## CarPlayTemplateUIHost

> `/System/Library/CoreServices/CarPlayTemplateUIHost.app/CarPlayTemplateUIHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd0ec` | `0xd050` | **`-0x9c`** |
| `__TEXT.__objc_methname` | `0x3db7` | `0x3e01` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x612` | `0x5ce` | **`-0x44`** |
| `__DATA_CONST.__cfstring` | `0x420` | `0x3e0` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0xcd0` | `0xd01` | **`+0x31`** |
| `__TEXT.__objc_methlist` | `0x135c` | `0x138c` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3aa0` | `0x3ac8` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2c00` | `0x2c20` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2d8` | `0x2c0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0xf20` | `0xf28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-571.3.0.0.0
+574.2.0.0.0

-  Functions: 367
+  Functions: 369

-  CStrings:  918
+  CStrings:  919
CStrings:
+ "templateInstance:willHideMapViewAnimated:"
+ "templateInstance:willShowMapViewAnimated:"
+ "v28@0:8@\"CPSTemplateInstance\"16B24"
+ "v28@0:8@16B24"
- "CPMapTemplateWillHideNotification"
- "CPMapTemplateWillShowNotification"
- "boolValue"
```
