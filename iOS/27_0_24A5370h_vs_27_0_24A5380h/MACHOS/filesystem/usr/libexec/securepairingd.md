## securepairingd

> `/usr/libexec/securepairingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x467d4` | `0x4c6d0` | **`+0x5efc`** |
| `__DATA.__bss` | `0xdc20` | `0xe9a0` | **`+0xd80`** |
| `__TEXT.__const` | `0x7788` | `0x7e68` | **`+0x6e0`** |
| `__DATA_CONST.__const` | `0x42a0` | `0x46e8` | **`+0x448`** |
| `__TEXT.__eh_frame` | `0x2b58` | `0x2e00` | **`+0x2a8`** |
| `__DATA.__data` | `0x3052` | `0x3242` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x10ed` | `0x129d` | **`+0x1b0`** |
| `__TEXT.__swift5_typeref` | `0x167f` | `0x17f9` | **`+0x17a`** |
| `__TEXT.__unwind_info` | `0x1510` | `0x1660` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x1ee4` | `0x1fec` | **`+0x108`** |
| `__TEXT.__swift5_fieldmd` | `0x170c` | `0x17fc` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xf90` | `0x1060` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x3f0` | `0x4a4` | **`+0xb4`** |
| `__TEXT.__swift5_proto` | `0x75c` | `0x7d0` | **`+0x74`** |
| `__TEXT.__auth_stubs` | `0x1700` | `0x1770` | **`+0x70`** |
| `__DATA.__objc_const` | `0x1938` | `0x1978` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x824` | `0x864` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xb88` | `0xbc0` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x2a8` | `0x2d8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x1c8` | `0x1ef` | **`+0x27`** |
| `__TEXT.__swift5_types` | `0x268` | `0x280` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x7c` | `0x94` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x4c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-59.0.0.0.0
+61.0.0.0.0

-  Functions: 1759
-  Symbols:   570
-  CStrings:  250
+  Functions: 1861
+  Symbols:   577
+  CStrings:  265
Symbols:
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss18_DictionaryStorageC4copy8originalAByxq_Gs05__RawaB0C_tFZ
+ _$ss18_DictionaryStorageC6resize8original8capacity4moveAByxq_Gs05__RawaB0C_SiSbtFZ
+ _$ss22KeyedDecodingContainerV15decodeIfPresent_6forKeys6UInt32VSgAFm_xtKF
+ _$ss22KeyedEncodingContainerV15encodeIfPresent_6forKeyys6UInt32VSg_xtKF
+ _$ss53KEY_TYPE_OF_DICTIONARY_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _os_transaction_create
CStrings:
+ ".sigmaLeadPairing("
+ "Invalid key value while decoding result type for unpairAll"
+ "SecurePairingXPCService.ServiceState.addSession session=%s"
+ "SecurePairingXPCService.ServiceState.removeSession session=%s"
+ "SecurePairingXPCService.ServiceState.setClientCancelled()"
+ "awaitSessionRemoval(for:)"
+ "com.apple.securepairing.pairingSession.lead."
+ "created transaction and parked task for %s"
+ "processing XPC request sigmaSessionEnded for pairingID=%llu"
+ "released transaction and parked task for %s"
+ "session not added - client cancelled"
+ "sessionContinuations"
+ "sigmaSessionEnded"
+ "unpairAll"
+ "useDak"
```
