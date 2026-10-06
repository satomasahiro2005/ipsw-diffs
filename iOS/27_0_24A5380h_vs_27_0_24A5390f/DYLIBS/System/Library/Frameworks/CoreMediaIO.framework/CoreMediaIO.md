## CoreMediaIO

> `/System/Library/Frameworks/CoreMediaIO.framework/CoreMediaIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ea8c` | `0x3eb2c` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x270` | `0x280` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc50` | `0xc58` | **`+0x8`** |

### Other Changes

```diff

-5631.0.0.0.0
+5633.0.0.0.0

-  Symbols:   1854
+  Symbols:   1855
Symbols:
+ ___block_descriptor_48_e8_32o40o_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24ls32l8s40l8
+ ___block_descriptor_64_e8_32o40o48o56o_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8s48l8s56l8
+ _objc_release_x24
- ___block_descriptor_40_e8_32o_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24ls32l8
- ___block_descriptor_56_e8_32o40o48o_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8s48l8
Functions:
~ -[CMIOExtensionSessionStream updatePropertyStates:streamID:] : 380 -> 384
~ -[CMIOExtensionSessionStream delegate] : 8 -> 44
~ -[CMIOExtensionSessionDevice updateStreamIDs:] : 1016 -> 1028
~ ___46-[CMIOExtensionSessionDevice updateStreamIDs:]_block_invoke : 252 -> 244
~ -[CMIOExtensionSessionDevice delegate] : 8 -> 44
~ -[CMIOExtensionSessionProvider delegate] : 8 -> 44
~ -[CMIOExtensionSessionProvider extension:didFailWithError:] : 104 -> 108
~ -[CMIOExtensionSessionProvider extensionHasBeenInvalidated:] : 240 -> 244
~ -[CMIOExtensionSessionProvider extension:pluginPropertiesChanged:] : 328 -> 332
~ -[CMIOExtensionSessionProvider extension:availableDevicesChanged:] : 968 -> 988
~ ___66-[CMIOExtensionSessionProvider extension:availableDevicesChanged:]_block_invoke : 316 -> 304
~ ___41-[CMIOExtensionSession initWithDelegate:]_block_invoke : 720 -> 744
```
