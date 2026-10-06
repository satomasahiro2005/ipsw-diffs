## UARPAssetManager

> `/System/Library/PrivateFrameworks/UARPAssetManager.framework/UARPAssetManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4420` | `0x4e10` | **`+0x9f0`** |
| `__AUTH_CONST.__objc_const` | `0xe40` | `0xfa0` | **`+0x160`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x140` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x230` | `0x140` | **`-0xf0`** |
| `__TEXT.__objc_methlist` | `0x74c` | `0x834` | **`+0xe8`** |
| `__AUTH_CONST.__cfstring` | `0x5c0` | `0x680` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x5c9` | `0x62f` | **`+0x66`** |
| `__TEXT.__oslogstring` | `0xc8` | `0x11b` | **`+0x53`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b8` | `0x400` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x250` | `0x288` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x84` | `0x94` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1d4` | `0x1dc` | **`+0x8`** |

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 137
-  Symbols:   352
-  CStrings:  66
+  Functions: 155
+  Symbols:   385
+  CStrings:  73
Symbols:
+ +[UARPEndpointPersonalityiCloud supportsSecureCoding]
+ -[UARPAssetManagerCacheConfiguration initWithModel:hwFusing:domain:assetVersion:filePath:usePallas:useiCloud:internalVersion:restoreVersion:]
+ -[UARPAssetManagerCacheConfiguration model]
+ -[UARPAssetManagerCacheConfiguration useiCloud]
+ -[UARPAssetManagerClient getAssetURLForPersonality:releaseNotes:]
+ -[UARPAssetManagerClient getReleaseNotesAssetURLForPersonality:]
+ -[UARPEndpointPersonalityiCloud .cxx_destruct]
+ -[UARPEndpointPersonalityiCloud containerID]
+ -[UARPEndpointPersonalityiCloud copyWithZone:]
+ -[UARPEndpointPersonalityiCloud description]
+ -[UARPEndpointPersonalityiCloud encodeWithCoder:]
+ -[UARPEndpointPersonalityiCloud hash]
+ -[UARPEndpointPersonalityiCloud initWithCoder:]
+ -[UARPEndpointPersonalityiCloud initWithProductGroup:productNumber:domain:]
+ -[UARPEndpointPersonalityiCloud isEqual:]
+ -[UARPEndpointPersonalityiCloud isPersonalityMatch:]
+ -[UARPEndpointPersonalityiCloud productGroup]
+ -[UARPEndpointPersonalityiCloud productNumber]
+ -[UARPEndpointPersonalityiCloud setContainerID:]
+ GCC_except_table18
+ GCC_except_table22
+ GCC_except_table29
+ _OBJC_CLASS_$_UARPEndpointPersonalityiCloud
+ _OBJC_IVAR_$_UARPAssetManagerCacheConfiguration._model
+ _OBJC_IVAR_$_UARPAssetManagerCacheConfiguration._useiCloud
+ _OBJC_IVAR_$_UARPEndpointPersonalityiCloud._containerID
+ _OBJC_IVAR_$_UARPEndpointPersonalityiCloud._productGroup
+ _OBJC_IVAR_$_UARPEndpointPersonalityiCloud._productNumber
+ _OBJC_METACLASS_$_UARPEndpointPersonalityiCloud
+ __OBJC_$_CLASS_METHODS_UARPEndpointPersonalityiCloud
+ __OBJC_$_INSTANCE_METHODS_UARPEndpointPersonalityiCloud
+ __OBJC_$_INSTANCE_VARIABLES_UARPEndpointPersonalityiCloud
+ __OBJC_$_PROP_LIST_UARPEndpointPersonalityiCloud
+ __OBJC_CLASS_RO_$_UARPEndpointPersonalityiCloud
+ __OBJC_METACLASS_RO_$_UARPEndpointPersonalityiCloud
+ ___62-[UARPAssetManagerClient getSandboxExtensionTokenForAssetURL:]_block_invoke_2
+ ___65-[UARPAssetManagerClient getAssetURLForPersonality:releaseNotes:]_block_invoke
+ ___65-[UARPAssetManagerClient getAssetURLForPersonality:releaseNotes:]_block_invoke_2
+ _createiCloudEndpointPersonality
- -[UARPAssetManagerCacheConfiguration appleModelNumber]
- -[UARPAssetManagerCacheConfiguration initWithAppleModelNumber:hwFusing:domain:assetVersion:filePath:usePallas:internalVersion:restoreVersion:]
- GCC_except_table20
- GCC_except_table23
- _OBJC_IVAR_$_UARPAssetManagerCacheConfiguration._appleModelNumber
- ___52-[UARPAssetManagerClient getAssetURLForPersonality:]_block_invoke
CStrings:
+ "-[UARPAssetManagerClient getAssetURLForPersonality:releaseNotes:]"
+ "<%@: model=%@ fusing=%@ domain=%@ pallas=%d icloud=%d vers=%@ file=%@ internal=%d restoreVersion=%@>"
+ "<%@: pg/pn=%@ domain=%@ "
+ "Domain %@, Product Group %@, Product Number %@ required for personality"
+ "Model Number %@, Serial Number %@, HW Fusing %@, Domain %@ required for personality"
+ "container=%@ "
+ "containerID"
+ "model"
+ "productGroup"
+ "productNumber"
+ "useiCloud"
- "-[UARPAssetManagerClient getAssetURLForPersonality:]"
- "<%@: model=%@ fusing=%@ domain=%@ pallas=%d vers=%@ file=%@ internal=%d restoreVersion=%@>"
- "Model Number %@, Serial Number %@, HW Fusing %@ required for personality"
- "appleModelNumber"
```
