## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2b8` | `0xe3f8` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x15b8` | `0x15f8` | **`+0x40`** |
| `__DATA.__bss` | `0x9c0` | `0x9e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x189f` | `0x18bb` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4626.103.0.0.0
+4630.1.102.0.0

-  Functions: 635
-  Symbols:   376
-  CStrings:  689
+  Functions: 641
+  Symbols:   378
+  CStrings:  691
Symbols:
+ _SBLogResourceConditions
+ _SBLogShipMode
CStrings:
+ "ResourceConditions"
+ "ShipMode"
```
