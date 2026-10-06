## Rhine

> `/System/Library/ScreenReader/BrailleTables/Rhine.brailletable/Rhine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x200` | `0x240` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3a0` | `0x3e0` | **`+0x40`** |
| `__TEXT.__text` | `0x1ef68` | `0x1efa0` | **`+0x38`** |
| `__DATA_CONST.__objc_arraydata` | `0x58` | `0x78` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x600` | `0x620` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-21.0.0.0.0
+22.0.0.0.0

-  Symbols:   290
-  CStrings:  4217
+  Symbols:   291
+  CStrings:  4219
Symbols:
+ _OBJC_CLASS_$_NSSet
Functions:
~ sub_1ef40 : 88 -> 144
CStrings:
+ "containsObject:"
+ "setWithObjects:"
```
