## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b538` | `0x1b728` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x473d` | `0x476c` | **`+0x2f`** |
| `__TEXT.__objc_stubs` | `0x53c0` | `0x53a0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x790` | `0x7a8` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__objc_doubleobj` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x5fe8` | `0x5fd8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x7b0` | `0x7bc` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x16d0` | `0x16c8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Symbols:   443
-  CStrings:  1402
+  Symbols:   447
+  CStrings:  1401
Symbols:
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _PAMediaConversionServiceOptionColorSpaceKey
+ _PAMediaConversionServiceOptionFormatConversionOnlyKey
+ _PAMediaConversionServiceOptionScaleFactorKey
Functions:
~ sub_100002ea0 -> sub_100002ef0 : 1540 -> 1600
~ sub_100008958 -> sub_1000089e4 : 376 -> 436
~ sub_100008ad0 -> sub_100008b98 : 408 -> 524
~ sub_100008c68 -> sub_100008da4 : 1808 -> 1956
~ sub_100009378 -> sub_100009548 : 196 -> 256
~ sub_10000943c -> sub_100009648 : 284 -> 336
CStrings:
+ "File Provider cache cleanup: unable to determine relationship of %@ to document storage root, leaving in place: %@"
- "File Provider cache cleanup: removed empty domain root directory %@"
- "standardizedURL"
```
