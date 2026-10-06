## BookStoreUI

> `/private/var/staged_system_apps/Books.app/Frameworks/BookStoreUI.framework/BookStoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x3ddd` | `0x3e3d` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1b4c5` | `0x1b4b5` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x3500` | `0x3508` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6643.0.0.0.0
+6647.0.0.0.0

-  Symbols:   1322
-  CStrings:  6512
+  Symbols:   1323
+  CStrings:  6513
Symbols:
+ _OBJC_CLASS_$_BCInAppMessages
Functions:
~ sub_4a998 : 592 -> 564
~ sub_5237c -> sub_52360 : 448 -> 540
~ sub_1c56b0 -> sub_1c56f0 : 3036 -> 2972
CStrings:
+ "BKDisableInAppMessages set — dropping pushed engagement update for placement: %{public}@"
+ "disabled"
- "setPrefersEdgeAttachedInCompactHeight:"
```
