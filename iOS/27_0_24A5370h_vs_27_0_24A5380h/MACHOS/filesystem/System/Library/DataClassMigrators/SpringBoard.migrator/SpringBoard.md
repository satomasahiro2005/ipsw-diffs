## SpringBoard

> `/System/Library/DataClassMigrators/SpringBoard.migrator/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe25c` | `0xe2b8` | **`+0x5c`** |
| `__TEXT.__objc_methname` | `0x19bd` | `0x19e1` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x1980` | `0x19a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x63c` | `0x64c` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4621.0.0.0.0
+4626.103.0.0.0

-  Functions: 634
+  Functions: 635

-  CStrings:  688
+  CStrings:  689
CStrings:
+ "shouldRecreateSystemAppLaunchImages"
```
