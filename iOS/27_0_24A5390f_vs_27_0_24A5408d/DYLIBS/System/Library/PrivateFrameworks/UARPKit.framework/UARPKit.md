## UARPKit

> `/System/Library/PrivateFrameworks/UARPKit.framework/UARPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143f0` | `0x14998` | **`+0x5a8`** |
| `__AUTH_CONST.__objc_const` | `0x1e90` | `0x1f80` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x14f8` | `0x15a0` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0xb40` | `0xbc0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1dea` | `0x1e26` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0xd88` | `0xdc0` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x1a0` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x420` | `0x428` | **`+0x8`** |

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 518
-  Symbols:   778
-  CStrings:  249
+  Functions: 532
+  Symbols:   799
+  CStrings:  253
Symbols:
+ -[UARPDevice transportDomain]
+ -[UARPDevice(FeatureSupport) setDeviceTransportDomain:]
+ -[UARPDeviceConfiguration productGroup]
+ -[UARPDeviceConfiguration productNumber]
+ -[UARPDeviceConfiguration setProductGroup:]
+ -[UARPDeviceConfiguration setProductNumber:]
+ -[UARPDeviceManager productGroup:endpointIndex:]
+ -[UARPDeviceManager productGroup:endpointIndex:componentIndex:]
+ -[UARPDeviceManager productNumber:endpointIndex:]
+ -[UARPDeviceManager productNumber:endpointIndex:componentIndex:]
+ -[UARPHostEndpointProperties assetIdentifier]
+ -[UARPHostEndpointProperties setAssetIdentifier:]
+ -[UARPHostEndpointProperties setTransportDomain:]
+ -[UARPHostEndpointProperties transportDomain]
+ GCC_except_table101
+ GCC_except_table104
+ GCC_except_table107
+ GCC_except_table110
+ GCC_except_table113
+ GCC_except_table116
+ GCC_except_table119
+ GCC_except_table124
+ GCC_except_table127
+ GCC_except_table71
+ GCC_except_table72
+ GCC_except_table87
+ GCC_except_table92
+ GCC_except_table95
+ GCC_except_table98
+ _OBJC_IVAR_$_UARPDevice._transportDomain
+ _OBJC_IVAR_$_UARPDeviceConfiguration._productGroup
+ _OBJC_IVAR_$_UARPDeviceConfiguration._productNumber
+ _OBJC_IVAR_$_UARPHostEndpointProperties._assetIdentifier
+ _OBJC_IVAR_$_UARPHostEndpointProperties._transportDomain
+ _objc_sync_enter
+ _objc_sync_exit
- GCC_except_table100
- GCC_except_table103
- GCC_except_table106
- GCC_except_table109
- GCC_except_table112
- GCC_except_table115
- GCC_except_table120
- GCC_except_table123
- GCC_except_table65
- GCC_except_table68
- GCC_except_table83
- GCC_except_table88
- GCC_except_table91
- GCC_except_table94
- GCC_except_table97
CStrings:
+ "ProductGroup"
+ "ProductNumber"
+ "assetIdentifier"
+ "transportDomain"
```
