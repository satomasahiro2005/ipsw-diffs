## FrontBoardServices

> `/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98c98` | `0x98ed4` | **`+0x23c`** |
| `__TEXT.__cstring` | `0xc104` | `0xc181` | **`+0x7d`** |
| `__AUTH_CONST.__objc_const` | `0x100f8` | `0x10128` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x8688` | `0x86a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2ae0` | `0x2af8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d68` | `0x3d78` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1e30` | `0x1e40` | **`+0x10`** |
| `__DATA.__bss` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa58` | `0xa5c` | **`+0x4`** |

### Other Changes

```diff

-1153.2.1.0.0
+1153.2.2.0.0

-  Functions: 4379
-  Symbols:   6496
-  CStrings:  1940
+  Functions: 4385
+  Symbols:   6504
+  CStrings:  1942
Symbols:
+ -[_FBSSnapshotContext alternateLayout]
+ -[_FBSSnapshotContext setAlternateLayout:]
+ GCC_except_table80
+ GCC_except_table89
+ _OBJC_IVAR_$__FBSSnapshotContext._alternateLayout
+ ___getkCASnapshotAlternateLayoutSymbolLoc_block_invoke
+ _getkCASnapshotAlternateLayout
+ _getkCASnapshotAlternateLayoutSymbolLoc
+ _getkCASnapshotAlternateLayoutSymbolLoc.ptr
- GCC_except_table53
CStrings:
+ "kCASnapshotAlternateLayout"
+ "typeof (((typeof (kCASnapshotAlternateLayout) (*)(void))0)()) getkCASnapshotAlternateLayout(void)"
```
