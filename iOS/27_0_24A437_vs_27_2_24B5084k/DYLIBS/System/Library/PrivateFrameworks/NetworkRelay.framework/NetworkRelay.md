## NetworkRelay

> `/System/Library/PrivateFrameworks/NetworkRelay.framework/NetworkRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b6f4` | `0x7c5c8` | **`+0xed4`** |
| `__TEXT.__cstring` | `0x104d4` | `0x107bc` | **`+0x2e8`** |
| `__TEXT.__gcc_except_tab` | `0xb60` | `0xbbc` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0xa10` | `0xa48` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x5200` | `0x5230` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xd70` | `0xda0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1fc4` | `0x1ff4` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x51e0` | `0x5200` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x10e0` | `0x1100` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x560` | `0x564` | **`+0x4`** |

### Other Changes

```diff

-914.0.34.0.4
+914.40.22.0.0

-  Functions: 1064
-  Symbols:   2287
-  CStrings:  1997
+  Functions: 1074
+  Symbols:   2302
+  CStrings:  2008
Symbols:
+ -[NRDevicePairingManager checkAdditionalData:]
+ -[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]
+ -[NRDevicePairingManager updateAdditionalData:withCompletion:]
+ -[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:additionalData:withCompletion:]
+ -[NRDevicePairingManagerMux updateAdditionalDataForPairingManager:additionalData:withCompletion:]
+ -[NRPairedDevice additionalData]
+ -[NRPairedDevice setAdditionalData:]
+ GCC_except_table705
+ GCC_except_table713
+ GCC_except_table718
+ GCC_except_table722
+ GCC_except_table727
+ GCC_except_table740
+ GCC_except_table744
+ GCC_except_table748
+ GCC_except_table752
+ GCC_except_table773
+ GCC_except_table776
+ GCC_except_table780
+ GCC_except_table787
+ GCC_except_table789
+ GCC_except_table791
+ GCC_except_table793
+ GCC_except_table796
+ GCC_except_table798
+ GCC_except_table800
+ GCC_except_table856
+ GCC_except_table858
+ GCC_except_table873
+ _OBJC_IVAR_$_NRPairedDevice._additionalData
+ ___103-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:additionalData:withCompletion:]_block_invoke
+ ___62-[NRDevicePairingManager updateAdditionalData:withCompletion:]_block_invoke
+ ___62-[NRDevicePairingManager updateAdditionalData:withCompletion:]_block_invoke_2
+ ___62-[NRDevicePairingManager updateAdditionalData:withCompletion:]_block_invoke_3
+ ___87-[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]_block_invoke
+ ___87-[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]_block_invoke_2
+ ___87-[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]_block_invoke_3
+ ___97-[NRDevicePairingManagerMux updateAdditionalDataForPairingManager:additionalData:withCompletion:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ _nrXPCKeyAdditionalData
- -[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:withCompletion:]
- GCC_except_table703
- GCC_except_table711
- GCC_except_table716
- GCC_except_table720
- GCC_except_table724
- GCC_except_table730
- GCC_except_table738
- GCC_except_table742
- GCC_except_table765
- GCC_except_table768
- GCC_except_table772
- GCC_except_table777
- GCC_except_table779
- GCC_except_table781
- GCC_except_table783
- GCC_except_table788
- GCC_except_table790
- GCC_except_table846
- GCC_except_table848
- GCC_except_table863
- ___72-[NRDevicePairingManager startPairingDevice:withCompletion:resultBlock:]_block_invoke
- ___72-[NRDevicePairingManager startPairingDevice:withCompletion:resultBlock:]_block_invoke_2
- ___72-[NRDevicePairingManager startPairingDevice:withCompletion:resultBlock:]_block_invoke_3
- ___88-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:withCompletion:]_block_invoke
CStrings:
+ "%@: additionalData length %lu exceeds maximum of %lu bytes"
+ "%s%.30s:%-4d Update additional data could not deliver message %@, error %@"
+ "%s%.30s:%-4d Update additional data received unexpected XPC object: %@"
+ "%s%.30s:%-4d Update additional data request with no XPC connection"
+ "-[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]"
+ "-[NRDevicePairingManager startPairingDevice:additionalData:withCompletion:resultBlock:]_block_invoke_2"
+ "-[NRDevicePairingManager updateAdditionalData:withCompletion:]"
+ "-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:additionalData:withCompletion:]"
+ "-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:additionalData:withCompletion:]_block_invoke"
+ "-[NRDevicePairingManagerMux updateAdditionalDataForPairingManager:additionalData:withCompletion:]"
+ "-[NRDevicePairingManagerMux updateAdditionalDataForPairingManager:additionalData:withCompletion:]_block_invoke"
+ "AdditionalData"
+ "Update additional data received unexpected XPC object"
+ "Update additional data response missing or invalid result"
+ "additionalData"
- "-[NRDevicePairingManager startPairingDevice:withCompletion:resultBlock:]"
- "-[NRDevicePairingManager startPairingDevice:withCompletion:resultBlock:]_block_invoke_2"
- "-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:withCompletion:]"
- "-[NRDevicePairingManagerMux startPairingForPairingManager:pairingTarget:withCompletion:]_block_invoke"
```
