## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9011c` | `0x907d4` | **`+0x6b8`** |
| `__DATA_CONST.__const` | `0x2610` | `0x26d8` | **`+0xc8`** |
| `__AUTH_CONST.__const` | `0xad0` | `0xb10` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1e98` | `0x1ed0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0xb68` | `0xb94` | **`+0x2c`** |
| `__TEXT.__eh_frame` | `0x8f0` | `0x918` | **`+0x28`** |
| `__TEXT.__cstring` | `0xe685` | `0xe6a5` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1130` | `0x1148` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3a00` | `0x3a18` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x57ec` | `0x5804` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x1511e` | `0x1510e` | **`-0x10`** |

### Other Changes

```diff

-448.125.5.2.0
+448.125.9.0.0

-  Functions: 3209
-  Symbols:   4217
-  CStrings:  2862
+  Functions: 3220
+  Symbols:   4235
+  CStrings:  2863
Symbols:
+ -[CDPDPCSController _sendGeneratePDPBlob:completion:]
+ -[CDPDPCSController _sendSetupPDPIdentities:completion:]
+ GCC_except_table29
+ GCC_except_table32
+ GCC_except_table50
+ GCC_except_table52
+ GCC_except_table54
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke
+ ___53-[CDPDPCSController _sendGeneratePDPBlob:completion:]_block_invoke_2
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_2
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_3
+ ___56-[CDPDPCSController _sendSetupPDPIdentities:completion:]_block_invoke_4
+ ___block_descriptor_48_e8_32bs40r_e20_v24?0q8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16lr40l8s32l8
+ ___block_descriptor_48_e8_32bs40r_e28_v24?0"NSData"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32bs40r_e30_v24?0"NSNumber"8"NSError"16lr40l8s32l8
+ ___block_descriptor_56_e8_32s40r48w_e35_v16?0?<v?"NSNumber""NSError">8lw48l8s32l8r40l8
+ ___block_descriptor_56_e8_32s40s48r_e33_v16?0?<v?"NSData""NSError">8ls32l8s40l8r48l8
+ _kAAAnalyticsEventCustodianHealthCheckOwnerCleanupOrphanedCustodian
+ _kDataAccessRecoveryContactSuggestionFamily
+ _kDataAccessRecoveryContactSuggestionMegadome
- GCC_except_table30
- GCC_except_table38
- GCC_except_table40
- ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16ls32l8
CStrings:
+ "%@: Renewed credentials, retrying PDP blob generation"
+ "v16@?0@?<v@?@\"NSData\"@\"NSError\">8"
- "Generate PDP Blob retry completed with blob length=%lu error=%@"
```
