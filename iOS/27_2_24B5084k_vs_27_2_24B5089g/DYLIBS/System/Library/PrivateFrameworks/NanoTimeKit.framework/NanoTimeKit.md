## NanoTimeKit

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/NanoTimeKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ff8cc` | `0x2ffacc` | **`+0x200`** |
| `__AUTH.__objc_data` | `0xa240` | `0xa178` | **`-0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x7320` | `0x73e8` | **`+0xc8`** |
| `__DATA_DIRTY.__data` | `0x13a8` | `0x1418` | **`+0x70`** |
| `__DATA.__bss` | `0x5b60` | `0x5b20` | **`-0x40`** |
| `__DATA.__data` | `0x50a0` | `0x5060` | **`-0x40`** |
| `__DATA_DIRTY.__bss` | `0x4b60` | `0x4ba0` | **`+0x40`** |
| `__AUTH.__data` | `0x350` | `0x320` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x53a40` | `0x53a60` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x30030` | `0x30048` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d40` | `0x14d50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd538` | `0xd548` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x39ac` | `0x39b0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2483.543.0.0.0
+2483.544.0.0.0

-  Functions: 20356
-  Symbols:   34047
+  Functions: 20358
+  Symbols:   34050
Symbols:
+ -[NTKFace _currentResourceDirectory]
+ -[NTKFace _getResourceDirectory:isOwned:]
+ -[NTKFace _setResourceDirectory:isOwned:]
+ GCC_except_table105
+ GCC_except_table130
+ GCC_except_table162
+ GCC_except_table173
+ GCC_except_table175
+ GCC_except_table196
+ GCC_except_table292
+ GCC_except_table308
+ GCC_except_table313
+ GCC_except_table335
+ GCC_except_table378
+ GCC_except_table379
+ GCC_except_table386
+ GCC_except_table394
+ GCC_except_table71
+ _OBJC_IVAR_$_NTKFace._resourceDirectoryLock
- -[NTKFace _setResourceDirectory:]
- GCC_except_table102
- GCC_except_table127
- GCC_except_table136
- GCC_except_table159
- GCC_except_table170
- GCC_except_table190
- GCC_except_table289
- GCC_except_table305
- GCC_except_table310
- GCC_except_table332
- GCC_except_table374
- GCC_except_table375
- GCC_except_table384
- GCC_except_table392
- GCC_except_table68
CStrings:
+ "description=NanoTimeKit-2483.544"
- "description=NanoTimeKit-2483.543"
```
