## SearchFoundation

> `/System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c4854` | `0x3c4ccc` | **`+0x478`** |
| `__AUTH_CONST.__objc_const` | `0xafa90` | `0xafb30` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x57964` | `0x579d4` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x8548` | `0x84d8` | **`-0x70`** |
| `__AUTH_CONST.__cfstring` | `0x12fe0` | `0x13000` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x79c8` | `0x79e0` | **`+0x18`** |
| `__TEXT.__cstring` | `0xbd30` | `0xbd40` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x45b0` | `0x45b8` | **`+0x8`** |

### Other Changes

```diff

-3600.56.21.0.0
+3600.56.26.0.0

-  Functions: 17804
-  Symbols:   33361
-  CStrings:  2489
+  Functions: 17809
+  Symbols:   33368
+  CStrings:  2490
Symbols:
+ -[SFImageReferenceData hasSharing_disabled]
+ -[SFImageReferenceData setSharing_disabled:]
+ -[SFImageReferenceData sharing_disabled]
+ -[_SFPBImageReferenceData setSharing_disabled:]
+ -[_SFPBImageReferenceData sharing_disabled]
+ GCC_except_table2844
+ GCC_except_table6562
+ GCC_except_table8184
+ _OBJC_IVAR_$_SFImageReferenceData._sharing_disabled
+ _OBJC_IVAR_$__SFPBImageReferenceData._sharing_disabled
- GCC_except_table2841
- GCC_except_table6559
- GCC_except_table8181
CStrings:
+ "sharingDisabled"
```
