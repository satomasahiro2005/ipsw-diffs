## GamepadHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/GamepadHIDServiceFilter.plugin/GamepadHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x420` | `0x460` | **`+0x40`** |
| `__TEXT.__text` | `0x27e0` | `0x2820` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x800` | `0x81b` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0x428` | `0x440` | **`+0x18`** |
| `__TEXT.__cstring` | `0x8c` | `0xa2` | **`+0x16`** |
| `__DATA.__objc_selrefs` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2f0` | `0x300` | **`+0x10`** |
| `__DATA.__objc_const` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-14.0.21.0.0
+14.0.24.0.0

-  Functions: 65
-  Symbols:   88
-  CStrings:  200
+  Functions: 66
+  Symbols:   89
+  CStrings:  203
Symbols:
+ ___kCFBooleanTrue
Functions:
~ sub_d68 : 292 -> 352
+ sub_2be4
CStrings:
+ "GameControllerSupport"
+ "endHaptics"
+ "propertyForKey:"
```
