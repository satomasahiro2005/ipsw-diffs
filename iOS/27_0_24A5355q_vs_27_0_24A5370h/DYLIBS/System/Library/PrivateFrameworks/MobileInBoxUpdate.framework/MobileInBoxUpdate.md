## MobileInBoxUpdate

> `/System/Library/PrivateFrameworks/MobileInBoxUpdate.framework/MobileInBoxUpdate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32264` | `0x332e4` | **`+0x1080`** |
| `__AUTH_CONST.__cfstring` | `0x1c80` | `0x1d40` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x2988` | `0x2a48` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x17c1` | `0x1871` | **`+0xb0`** |
| `__AUTH_CONST.__objc_intobj` | `0x1278` | `0x1308` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1868` | `0x18e8` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x43b8` | `0x4418` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xee8` | `0xf40` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xa98` | `0xae0` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x2828` | `0x2868` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2669` | `0x2699` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1fc` | `0x224` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x360` | `0x378` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x798` | `0x7a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b0` | **`+0x4`** |

### Other Changes

```diff

-253.0.0.0.0
+266.0.0.0.0

-  Functions: 1374
-  Symbols:   1895
-  CStrings:  483
+  Functions: 1401
+  Symbols:   1917
+  CStrings:  492
Symbols:
+ -[MIBUClient assetAudienceID:]
+ -[MIBUClient pallasServerURL:]
+ -[MIBUDeviceStatus personalized]
+ -[MIBUDeviceStatus setPersonalized:]
+ -[MIBUTestPreferences _consumeOneShotBoolForKey:]
+ -[MIBUTestPreferences btLTKTimeOffset]
+ -[MIBUTestPreferences consumeFailBTAuthThenReboot]
+ -[MIBUTestPreferences consumeRebootAfterBTAuth]
+ -[MIBUTestPreferences consumeRebootAfterBTDisconnect]
+ GCC_except_table104
+ GCC_except_table81
+ GCC_except_table85
+ GCC_except_table91
+ GCC_except_table98
+ _CFPreferencesSetValue
+ _CTParseLeafSPKI
+ _OBJC_IVAR_$_MIBUDeviceStatus._personalized
+ ___30-[MIBUClient assetAudienceID:]_block_invoke
+ ___30-[MIBUClient assetAudienceID:]_block_invoke_2
+ ___30-[MIBUClient pallasServerURL:]_block_invoke
+ ___30-[MIBUClient pallasServerURL:]_block_invoke_2
+ ___block_descriptor_48_e8_32r40r_e27_v24?0"NSURL"8"NSError"16lr32l8r40l8
+ ___block_descriptor_48_e8_32r40r_e30_v24?0"NSString"8"NSError"16lr32l8r40l8
+ _kMIBUNFCCommandRQFileNumbersKey
+ _kMIBUNFCCommandUseInternalSUConfigKey
- GCC_except_table83
- GCC_except_table90
- GCC_except_table96
CStrings:
+ "'"
+ "BTLTKTimeOffset"
+ "FailBTAuthThenReboot"
+ "Failed to deserialize file numbers from command"
+ "RQFileNumbers"
+ "RebootAfterBTAuth"
+ "RebootAfterBTDisconnect"
+ "UseInternalSUConfig"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
+ "v24@?0@\"NSURL\"8@\"NSError\"16"
- "&"
```
