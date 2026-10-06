## BiomeStreams

> `/System/Library/PrivateFrameworks/BiomeStreams.framework/BiomeStreams`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f8940` | `0x3f94e8` | **`+0xba8`** |
| `__DATA_DIRTY.__objc_data` | `0x1670` | `0x1eb8` | **`+0x848`** |
| `__AUTH.__objc_data` | `0x7b90` | `0x7398` | **`-0x7f8`** |
| `__TEXT.__oslogstring` | `0xbff0` | `0xc180` | **`+0x190`** |
| `__AUTH.__data` | `0x135d0` | `0x13498` | **`-0x138`** |
| `__AUTH_CONST.__objc_const` | `0x4d5c8` | `0x4d6f0` | **`+0x128`** |
| `__DATA_DIRTY.__data` | `0x1b8` | `0x298` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x14fcc` | `0x15074` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0xc468` | `0xc4d8` | **`+0x70`** |
| `__DATA.__data` | `0x9d60` | `0x9dc0` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xd7f8` | `0xd858` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x12bc` | `0x12ec` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2a940` | `0x2a968` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x9560` | `0x9580` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6130` | `0x6150` | **`+0x20`** |
| `__TEXT.__cstring` | `0x312e3` | `0x31303` | **`+0x20`** |
| `__TEXT.__const` | `0xad174` | `0xad164` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x184c` | `0x1858` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1090` | `0x1098` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xe98` | `0xea0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x978` | `0x980` | **`+0x8`** |

### Other Changes

```diff

-256.0.1.0.0
+258.0.0.0.0

-  Functions: 21956
-  Symbols:   44720
-  CStrings:  9193
+  Functions: 21977
+  Symbols:   44750
+  CStrings:  9199
Symbols:
+ -[BMComputeSourceChangeReporter .cxx_destruct]
+ -[BMComputeSourceChangeReporter _clientForStream:error:]
+ -[BMComputeSourceChangeReporter initWithAccount:]
+ -[BMComputeSourceChangeReporter init]
+ -[BMComputeSourceChangeReporter streamDeletionWithStreamIdentifier:remoteName:error:]
+ -[BMComputeSourceChangeReporter streamPrunedWithStreamIdentifier:remoteName:error:]
+ -[BMComputeSourceChangeReporter streamUpdatedWithStreamIdentifier:remoteName:error:]
+ -[BMComputeSourceClient eventsPrunedForAccount:remoteName:reason:error:]
+ -[BMComputeSourceClient streamUpdatedForAccount:remoteName:error:]
+ _$sSdySdSgxcSyRzlufcSbSpySdGXEfU_SbSPys4Int8VGXEfU_
+ _$sSdySdSgxcSyRzlufcSbSpySdGXEfU_SbSPys4Int8VGXEfU_TA
+ _$ss11_StringGutsV16_slowWithCStringyxxSPys4Int8VGq_YKXEq_YKs5ErrorR_r0_lFAFq_xRi_zRi0_zRi__Ri0__r0_lysAG_pxIsgyrzr_ABxsAG_psAG_pRs_r0_lIetMggrzo_Tpq5Sb_Tg507$sSPys4f5VGxs5G34_pIgyrzo_ACxsAD_pIegyrzr_lTRSb_TG5AFSbsAG_pIgyrzo_Tf1cn_n
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s17_NativeDictionaryVySSSiG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxr12_YKXEfU_s17_kl10VySSSiG_s5M4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyAnLIsgyrzr_Tf1nc_n
+ _$ss17_NativeDictionaryV6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5ErrorRd__lFADs13_UnsafeBitsetVqd__YKXEfU_SS_Sis5NeverOTG5TA
+ _$ss17_NativeDictionaryV6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5ErrorRd__lFADs13_UnsafeBitsetVqd__YKXEfU_SS_Sis5NeverOTg5
+ _BMUseCaseSync
+ _OBJC_CLASS_$_BMComputeSourceChangeReporter
+ _OBJC_IVAR_$_BMComputeSourceChangeReporter._account
+ _OBJC_IVAR_$_BMComputeSourceChangeReporter._clientsByStream
+ _OBJC_IVAR_$_BMComputeSourceChangeReporter._lock
+ _OBJC_METACLASS_$_BMComputeSourceChangeReporter
+ __OBJC_$_INSTANCE_METHODS_BMComputeSourceChangeReporter
+ __OBJC_$_INSTANCE_VARIABLES_BMComputeSourceChangeReporter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BMViewEventReporter
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BMViewEventReporter
+ __OBJC_CLASS_PROTOCOLS_$_BMComputeSourceChangeReporter
+ __OBJC_CLASS_RO_$_BMComputeSourceChangeReporter
+ __OBJC_LABEL_PROTOCOL_$_BMViewEventReporter
+ __OBJC_METACLASS_RO_$_BMComputeSourceChangeReporter
+ __OBJC_PROTOCOL_$_BMViewEventReporter
+ ___66-[BMComputeSourceClient streamUpdatedForAccount:remoteName:error:]_block_invoke
+ ___72-[BMComputeSourceClient eventsPrunedForAccount:remoteName:reason:error:]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8lr40l8s32l8
- _$ss11_StringGutsV16_slowWithCStringyxxSPys4Int8VGq_YKXEq_YKs5ErrorR_r0_lFAFq_xRi_zRi0_zRi__Ri0__r0_lysAG_pxIsgyrzr_ABxsAG_psAG_pRs_r0_lIetMggrzo_Tpq5Sb_Tg5024$sSdySdSgxcSyRzlufcSbSpyj6GXEfU_n5SPys4F7VGXEfU_SpySdGTf1cn_n
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s17_NativeDictionaryVySSSiG_s5NeverOTg506$ss17_kl51V6filteryAByxq_GSbx3key_q_5valuet_tqd__YKXEqd__YKs5i12Rd__lFADs13_ab19Vqd__YKXEfU_SS_Sis5M4OTG5ALxq_Sbq0_Ri_zRi0_zRi__Ri0__Ri_0_Ri0_0_r1_lySSSiANIsgnndzr_Tf1nc_n
- ___66-[BMComputeSourceClient eventsPrunedForAccount:remoteName:reason:]_block_invoke
CStrings:
+ "BMComputeSourceChangeReporter: no stream configuration for %@, cannot report changes: %@"
+ "BMComputeSourceClient for stream %@ XPC error in eventsPruned: %@"
+ "BMComputeSourceClient for stream %@ XPC error in streamUpdated: %@"
+ "BMComputeSourceClient not notifying biomed of change to %@: no downstream subscriptions in storage domain %@"
+ "BMComputeSourceClient stream updated for stream %@ remote %@"
+ "No stream configuration for %@"
```
