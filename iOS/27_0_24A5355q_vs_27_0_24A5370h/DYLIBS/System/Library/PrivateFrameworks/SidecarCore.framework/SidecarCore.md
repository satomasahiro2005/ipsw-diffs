## SidecarCore

> `/System/Library/PrivateFrameworks/SidecarCore.framework/SidecarCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13a7c` | `0x13c0c` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0x14a0` | `0x1500` | **`+0x60`** |
| `__TEXT.__cstring` | `0x10e6` | `0x113a` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x2a40` | `0x2a70` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1748` | `0x1760` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc38` | `0xc48` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x194` | `0x198` | **`+0x4`** |

### Other Changes

```diff

-400.34.0.0.0
+400.37.0.0.0

-  Functions: 613
-  Symbols:   1254
-  CStrings:  240
+  Functions: 615
+  Symbols:   1257
+  CStrings:  243
Symbols:
+ -[SidecarDevice initWithIdentifier:model:name:version:operatingSystemVersion:]
+ -[SidecarDevice operatingSystemVersion]
+ GCC_except_table293
+ GCC_except_table297
+ GCC_except_table369
+ GCC_except_table370
+ GCC_except_table390
+ GCC_except_table414
+ GCC_except_table438
+ _OBJC_IVAR_$_SidecarDevice._operatingSystemVersion
- GCC_except_table291
- GCC_except_table295
- GCC_except_table367
- GCC_except_table368
- GCC_except_table388
- GCC_except_table412
- GCC_except_table436
CStrings:
+ "operatingSystemMajorVersion"
+ "operatingSystemMinorVersion"
+ "operatingSystemPatchVersion"
```
