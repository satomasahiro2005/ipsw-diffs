## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x183538` | `0x183af0` | **`+0x5b8`** |
| `__TEXT.__oslogstring` | `0x3719f` | `0x37447` | **`+0x2a8`** |
| `__TEXT.__unwind_info` | `0x4368` | `0x4180` | **`-0x1e8`** |
| `__TEXT.__objc_methname` | `0xf395` | `0xf3d0` | **`+0x3b`** |
| `__TEXT.__objc_methtype` | `0x2f65` | `0x2f90` | **`+0x2b`** |
| `__DATA_CONST.__cfstring` | `0x6ae0` | `0x6b00` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6b64` | `0x6b84` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x8748` | `0x8760` | **`+0x18`** |
| `__TEXT.__cstring` | `0xd514` | `0xd52c` | **`+0x18`** |
| `__DATA.__objc_const` | `0xa700` | `0xa708` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x3238` | `0x3240` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 7999
-  Symbols:   10912
-  CStrings:  8372
+  Functions: 8002
+  Symbols:   10916
+  CStrings:  8382
Symbols:
+ -[ACCBLEPairingServerRemote updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-4a9991a1dabff1ec88b854bba177ca59.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-926c7c8eed6aa774dde7a87eca6ef6b8.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-b88bd8b451a6ac10f5ed15c8dcf643a1.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-e2d4021dab97e90b3ab60b61d36c2778.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-4cb81a2fc48f025948b06c14bfe09041.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-5f62a3c49b088d908991494029c23e4d.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-e7d5da0e673878f664a0dc0c6140339d.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-4817c88bfc24ac4e87840a930f1f9082.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-fcc48202b11d62f2295ba8aca4a58bbf.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-7c249877612c728b0d30fb85acc9ed74.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-ed78de4767bd3f6b493403088186a497.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-45c1f96350c7c7a6a494edcfd1d2faf1.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-d5b043df232bae2ad26bed790cc691f2.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-e0ae5cc4d90af5a3630370c3cd0f60c2.o)
+ ___mfi4Auth_endpoint_initSession_block_invoke
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
+ _oobPairing_control_setResolvedAccessoryBTAddress
+ _platform_blePairing_resolvedAccessoryBTAddressHandler
+ platform_blePairing_resolvedAccessoryBTAddressHandler
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-3c146408402adf9b532fced379a27bfa.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-6751bbf669d80cfe1f8af52bb79208ca.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-7b4b737d3e6c4a0ecb9c09439e7e06ba.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-f6d461b27af035aee53f5c11857f4fa9.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-3b3486b90529e549b387c6b2e87676dd.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-2d6d63ea14b02614994ae765fd829a4a.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-535ad379a4035e0af6e6429db12d54ad.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-269823d335f71d172dabfe6634885129.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-8f6578cf8e56bf9d20c7840e982c88ea.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-079083d325a8a21da18a2d61d4072464.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-aa2e0e5364711ad3b06dfe9addab82bc.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-50f2b7f4b6ecbdac9306fa1d92b34bb1.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-78a405a76682232fc1b98e74514134ed.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-2324335dbddb9551ee24c9aa84fe5e97.o)
- _mfi4Auth_endpoint_sendOutgoingData
- mfi4Auth_endpoint_sendOutgoingData
CStrings:
+ "%s: pairingDataMatch %d, bdAddrMatch %d, override %d"
+ "BLEPairing updateResolvedAccessoryBTAddress: accessoryUID %@, NOT RESERVED connHash %lu"
+ "BLEPairing updateResolvedAccessoryBTAddress: accessoryUID %@, blePairingUUID=%@, resolvedAccessoryBTAddress length=%lu"
+ "BLEPairing updateResolvedAccessoryBTAddress: invalid BT address length %lu"
+ "Check for WirelessCTA: Found match! donor %@, receiver %@, override %d"
+ "PretendWirelessCTAMatch"
+ "Set resolved BT address for endpoint: %@ bleUUID: %@, btAddress: %@"
+ "_mfi4Auth_endpoint_sendOutgoingData: %@"
+ "blePairing resolvedAccessoryBTAddress: %@, blePairingUUID=%@, resolvedAccessoryBTAddress=%@"
+ "blePairing resolvedAccessoryBTAddress: malloc failed for %@"
+ "findWirelessCTAReceiverCapableConnection: prefer %@ over %@ (cached pairing populated on candidate; prior empty candidate should have been cleaned up)"
+ "updateResolvedAccessoryBTAddress:blePairingUUID:btAddress:"
+ "v40@0:8@\"NSString\"16@\"NSData\"24@\"NSData\"32"
- "%s: pairingDataMatch %d, bdAddrMatch %d"
- "Check for WirelessCTA: Found match! donor %@, receiver %@"
- "mfi4Auth_endpoint_sendOutgoingData: %@"
```
