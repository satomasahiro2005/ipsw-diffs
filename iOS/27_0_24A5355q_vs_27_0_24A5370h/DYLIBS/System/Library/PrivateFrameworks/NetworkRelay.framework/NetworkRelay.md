## NetworkRelay

> `/System/Library/PrivateFrameworks/NetworkRelay.framework/NetworkRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77f2c` | `0x78998` | **`+0xa6c`** |
| `__TEXT.__cstring` | `0xfdb4` | `0xfec4` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x4f80` | `0x5080` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x5068` | `0x50f0` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x1ea4` | `0x1f1c` | **`+0x78`** |
| `__DATA.__bss` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0xe0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x9c8` | `0x9e8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1070` | `0x1088` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x790` | `0x7a0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xb3c` | `0xb48` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__const` | `0xce0` | `0xce8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x270` | `0x278` | **`+0x8`** |

### Other Changes

```diff

-890.0.0.0.7
+914.0.1.0.4

-  Functions: 1030
-  Symbols:   2234
-  CStrings:  1945
+  Functions: 1041
+  Symbols:   2253
+  CStrings:  1956
Symbols:
+ +[NRMeshIdentifier supportsSecureCoding]
+ -[NRMeshIdentifier copyWithZone:]
+ -[NRMeshIdentifier description]
+ -[NRMeshIdentifier encodeWithCoder:]
+ -[NRMeshIdentifier hash]
+ -[NRMeshIdentifier initWithCoder:]
+ -[NRMeshIdentifier isEqual:]
+ -[NRMeshInfo meshIdentifier]
+ -[NRMeshInfo setMeshIdentifier:]
+ GCC_except_table122
+ GCC_except_table125
+ GCC_except_table137
+ GCC_except_table26
+ GCC_except_table274
+ GCC_except_table329
+ GCC_except_table354
+ GCC_except_table445
+ GCC_except_table456
+ GCC_except_table692
+ GCC_except_table700
+ GCC_except_table705
+ GCC_except_table709
+ GCC_except_table713
+ GCC_except_table719
+ GCC_except_table72
+ GCC_except_table723
+ GCC_except_table727
+ GCC_except_table731
+ GCC_except_table754
+ GCC_except_table757
+ GCC_except_table761
+ GCC_except_table774
+ GCC_except_table779
+ GCC_except_table83
+ GCC_except_table832
+ GCC_except_table847
+ _NREndpointCanUseMultiplexedASForService
+ _NREndpointUsesMultiplexedASForNWSC
+ _OBJC_IVAR_$_NRDeviceMonitor._internalUsesMultiplexedASForNWSC
+ _OBJC_IVAR_$_NRMeshInfo._meshIdentifier
+ __OBJC_$_CLASS_METHODS_NRMeshIdentifier
+ __OBJC_$_CLASS_PROP_LIST_NRMeshIdentifier
+ __OBJC_CLASS_PROTOCOLS_$_NRMeshIdentifier
+ _getprogname
+ _malloc_type_realloc
+ _nrXPCKeyUsesMultiplexedASForNWSC
+ _nw_parameters_set_account_id
- GCC_except_table120
- GCC_except_table123
- GCC_except_table133
- GCC_except_table24
- GCC_except_table272
- GCC_except_table327
- GCC_except_table352
- GCC_except_table443
- GCC_except_table454
- GCC_except_table690
- GCC_except_table698
- GCC_except_table70
- GCC_except_table703
- GCC_except_table707
- GCC_except_table711
- GCC_except_table717
- GCC_except_table721
- GCC_except_table725
- GCC_except_table729
- GCC_except_table752
- GCC_except_table755
- GCC_except_table759
- GCC_except_table764
- GCC_except_table775
- GCC_except_table81
- GCC_except_table828
- GCC_except_table845
- _reallocf
CStrings:
+ "<NRMeshIdentifier: %@>"
+ "<NRMeshInfo: %p> interfaceName: %@, interfaceIndex: %u, meshIdentifier: %@, isRegistered: %@, devices: %lu, primaryAssistEnabled: %@, roomDistributorEnabled: %@"
+ "D-Relay"
+ "TerminusTest/Service"
+ "UsesMultiplexedASForNWSC"
+ "ids-control-channel"
+ "idstest/localdelivery/UTunDelivery"
+ "meshIdentifier"
+ "service-connector.%s.%u.%@"
+ "service-connector.asquic"
+ "service-connector.asquic.muxed"
+ "service-connector.tcp"
- "<NRMeshInfo: %p> interfaceName: %@, interfaceIndex: %u, isRegistered: %@, devices: %lu, primaryAssistEnabled: %@, roomDistributorEnabled: %@"
```
