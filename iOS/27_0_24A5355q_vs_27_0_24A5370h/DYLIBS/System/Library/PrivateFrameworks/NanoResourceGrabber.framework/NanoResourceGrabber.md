## NanoResourceGrabber

> `/System/Library/PrivateFrameworks/NanoResourceGrabber.framework/NanoResourceGrabber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x437c` | `0x3c48` | **`-0x734`** |
| `__TEXT.__oslogstring` | `0x85e` | `0x79d` | **`-0xc1`** |
| `__DATA_CONST.__const` | `0x298` | `0x220` | **`-0x78`** |
| `__TEXT.__gcc_except_tab` | `0xb8` | `0x68` | **`-0x50`** |
| `__TEXT.__cstring` | `0x440` | `0x3fe` | **`-0x42`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f0` | `0x3b8` | **`-0x38`** |
| `__DATA_CONST.__got` | `0x100` | `0xd8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x1c0` | `0x198` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x360` | `0x340` | **`-0x20`** |

### Other Changes

```diff

-116.0.0.0.0
+117.0.0.0.0

-  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
+  - /System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry

-  Functions: 116
-  Symbols:   258
-  CStrings:  83
+  Functions: 105
+  Symbols:   237
+  CStrings:  75
Symbols:
+ _OBJC_CLASS_$_PDRRegistry
- GCC_except_table7
- GCC_except_table9
- _NRDevicePropertyIsArchived
- _NRDevicePropertyLocalPairingDataStorePath
- _NRGWaitForActivePairedDeviceStorePath
- _OBJC_CLASS_$_NRPairedDeviceRegistry
- _OBJC_CLASS_$_NSKeyedArchiver
- _OBJC_CLASS_$_NSKeyedUnarchiver
- _OBJC_EHTYPE_$_NSException
- ___NRGWaitForActivePairedDeviceStorePath_block_invoke
- ___block_descriptor_40_e8_32bs_e18_v16?0"NSString"8ls32l8
- ___block_descriptor_40_e8_32bs_e29_v24?0"NSString"8"NSUUID"16ls32l8
- ___block_descriptor_40_e8_32s_e18_v16?0"NSString"8ls32l8
- ___gizmoBuildPath_block_invoke
- ___loadGizmoBuild_block_invoke
- ___saveGizmoBuild_block_invoke
- _gizmoBuildPath
- _loadGizmoBuild
- _objc_begin_catch
- _objc_end_catch
- _objc_retainAutoreleasedReturnValue
- _saveGizmoBuild
CStrings:
- "gizmoBuild.plist"
- "loadGizmoBuild: failed to load gizmo build from %@"
- "loadGizmoBuild: gizmoBuild = %@ %@"
- "saveGizmoBuild: NSKeyedArchiver fail"
- "saveGizmoBuild: writeToFile fail %@"
- "saveGizmoBuild: wrote %@ %@ to %@"
- "v16@?0@\"NSString\"8"
- "v24@?0@\"NSString\"8@\"NSUUID\"16"
```
