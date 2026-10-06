## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2b8` | `0xe088` | **`-0x230`** |
| `__TEXT.__gcc_except_tab` | `0x3a8` | `0x3d0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x498` | `0x478` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x1be0` | `0x1c00` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x330` | `0x350` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x48` | `0x30` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x320` | `0x330` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x670` | `0x680` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x211d` | `0x212c` | **`+0xf`** |
| `__DATA.__data` | `0x198` | `0x190` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x8d0` | `0x8d8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x348` | `0x350` | **`+0x8`** |
| `__TEXT.__const` | `0xb0` | `0xb2` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-1307.0.16.0.0
+1307.0.26.502.1

+  - /System/Library/PrivateFrameworks/BatteryDischarge.framework/BatteryDischarge

+  - /System/Library/PrivateFrameworks/EmbeddedDataReset.framework/EmbeddedDataReset

-  Functions: 295
-  Symbols:   200
-  CStrings:  820
+  Functions: 292
+  Symbols:   201
+  CStrings:  821
Symbols:
+ _objc_retainAutoreleasedReturnValue
CStrings:
+ "numberWithInt:"
```
