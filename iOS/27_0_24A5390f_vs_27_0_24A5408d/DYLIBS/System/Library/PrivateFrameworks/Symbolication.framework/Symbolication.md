## Symbolication

> `/System/Library/PrivateFrameworks/Symbolication.framework/Symbolication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb97c` | `0xbc230` | **`+0x8b4`** |
| `__TEXT.__gcc_except_tab` | `0x5884` | `0x596c` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0xdae0` | `0xdba0` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xcb80` | `0xcc20` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x11288` | `0x11308` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x3ee8` | `0x3f38` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2da0` | `0x2db8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x10d8` | `0x10e8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd9c` | `0xdac` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x69f0` | `0x6a00` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x39f8` | `0x39f0` | **`-0x8`** |

### Other Changes

```diff

-64578.92.1.0.0
+64578.100.1.0.0

-  Functions: 3375
-  Symbols:   6134
-  CStrings:  2899
+  Functions: 3381
+  Symbols:   6147
+  CStrings:  2906
Symbols:
+ -[VMUProcessDescription hasRootsPresent]
+ -[VMUProcessDescription setHasRootsPresent:]
+ -[VMUProcessDescription usesMTE]
+ -[VMUProcessObjectGraph hasRootsPresent]
+ -[VMUProcessObjectGraph setHasRootsPresent:]
+ -[VMUTask stripMTEPointer:]
+ -[VMUTask useMTEPointerStripping]
+ -[VMUTaskMemoryCache isExclaveCore]
+ GCC_except_table61
+ OBJC_IVAR_$_VMUVMRegion.is_mte_enabled
+ _OBJC_IVAR_$_VMUProcessDescription._dscInstallNames
+ _OBJC_IVAR_$_VMUProcessDescription._hasRootsPresent
+ _OBJC_IVAR_$_VMUProcessObjectGraph._hasRootsPresent
+ _OBJC_IVAR_$_VMUTask._targetUsesMTE
+ _OBJC_IVAR_$_VMUTask._targetUsesMTEInitialized
+ _OBJC_IVAR_$_VMUTaskMemoryScanner._hasRootsPresent
+ __ZZ32-[VMUProcessDescription usesMTE]E41osSecurityConfigGetForTaskFunctionPointer
+ __ZZ32-[VMUProcessDescription usesMTE]E9onceToken
+ ___32-[VMUProcessDescription usesMTE]_block_invoke
+ ___68-[VMUProcessDescription initWithVMUTaskMemoryCache:getBinariesList:]_block_invoke_4
+ ____variantForSwiftClass_block_invoke_7
+ ___block_descriptor_40_ea8_32s_e23_v16?0^{dyld_image_s=}8ls32l8
+ ___block_descriptor_56_e8_32r40r48w_e29_v32?0"VMUFieldInfo"8Q16^B24lw48l8r32l8r40l8
+ _dyld_image_get_installname
+ _dyld_shared_cache_for_each_image
- -[VMUProcessDescription targetUsesExtraPointerBits:]
- -[VMUTask stripExtraPointerBits:]
- -[VMUTask useExtraPointerStripping]
- -[VMUVMRegion isExtraBits]
- -[VMUVMRegion isJIT]
- -[VMUVMRegion isTPRO]
- OBJC_IVAR_$_VMUVMRegion.is_extra_bits
- _OBJC_IVAR_$_VMUTask._targetUsesExtraBits
- _OBJC_IVAR_$_VMUTask._targetUsesExtraBitsInitialized
- __ZZ52-[VMUProcessDescription targetUsesExtraPointerBits:]E41osSecurityConfigGetForTaskFunctionPointer
- __ZZ52-[VMUProcessDescription targetUsesExtraPointerBits:]E9onceToken
- ___52-[VMUProcessDescription targetUsesExtraPointerBits:]_block_invoke
CStrings:
+ " (MTE Enabled"
+ " (Roots Present)"
+ ", Roots Present"
+ "PropertyList.Element"
+ "PropertyList.Element Storage"
+ "buf"
+ "hasRootsPresent"
+ "v16@?0^{dyld_image_s=}8"
- " (MTE Enabled)"
```
