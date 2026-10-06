## Moments

> `/System/Library/PrivateFrameworks/Moments.framework/Moments`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78e48` | `0x796ec` | **`+0x8a4`** |
| `__DATA_DIRTY.__objc_data` | `0x3c0` | `0xaa0` | **`+0x6e0`** |
| `__AUTH.__objc_data` | `0x2080` | `0x1a68` | **`-0x618`** |
| `__AUTH_CONST.__objc_const` | `0xb828` | `0xb8f0` | **`+0xc8`** |
| `__TEXT.__cstring` | `0xe5ee` | `0xe69e` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x10c20` | `0x10cc0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x6d24` | `0x6db4` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x3cc` | `0x410` | **`+0x44`** |
| `__TEXT.__const` | `0x1008` | `0x1048` | **`+0x40`** |
| `__AUTH.__data` | `0x2b0` | `0x2e0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x30` | `0x60` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x34c0` | `0x34e8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x19d0` | `0x19f8` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x5683` | `0x5664` | **`-0x1f`** |
| `__TEXT.__swift5_fieldmd` | `0x5a8` | `0x5c4` | **`+0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x4a6` | `0x4c0` | **`+0x1a`** |
| `__DATA.__data` | `0xef0` | `0xed8` | **`-0x18`** |
| `__AUTH_CONST.__const` | `0x810` | `0x820` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x78` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2f1` | `0x2fd` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x960` | `0x968` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x20` | `0x24` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x50` | **`+0x4`** |

### Other Changes

```diff

-502.0.5.0.0
+502.0.8.0.0

-  Functions: 3045
-  Symbols:   6703
-  CStrings:  2678
+  Functions: 3071
+  Symbols:   6758
+  CStrings:  2684
Symbols:
+ +[MOFilePersistenceManager configSnapshotWithEventRetentionSeconds:]
+ -[MOFilePersistenceManager donateEventBundles:events:prediction:configSnapshot:error:]
+ -[MOFilePersistenceManager persistEventBundles:events:prediction:configSnapshot:error:]
+ _$s7Moments16MOConfigSnapshotC20supportsSecureCodingSbvgZ
+ _$s7Moments16MOConfigSnapshotC20supportsSecureCodingSbvgZTo
+ _$s7Moments16MOConfigSnapshotC20supportsSecureCodingSbvpZMV
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsACSd_tcfC
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsACSd_tcfCTj
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsACSd_tcfCTq
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsACSd_tcfc
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsACSd_tcfcTo
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsSdvg
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsSdvgTo
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsSdvpMV
+ _$s7Moments16MOConfigSnapshotC21eventRetentionSecondsSdvpWvd
+ _$s7Moments16MOConfigSnapshotC4hashSivg
+ _$s7Moments16MOConfigSnapshotC4hashSivgTo
+ _$s7Moments16MOConfigSnapshotC5coderACSgSo7NSCoderC_tcfC
+ _$s7Moments16MOConfigSnapshotC5coderACSgSo7NSCoderC_tcfCTj
+ _$s7Moments16MOConfigSnapshotC5coderACSgSo7NSCoderC_tcfCTq
+ _$s7Moments16MOConfigSnapshotC5coderACSgSo7NSCoderC_tcfc
+ _$s7Moments16MOConfigSnapshotC5coderACSgSo7NSCoderC_tcfcTo
+ _$s7Moments16MOConfigSnapshotC6encode4withySo7NSCoderC_tF
+ _$s7Moments16MOConfigSnapshotC6encode4withySo7NSCoderC_tFTo
+ _$s7Moments16MOConfigSnapshotC7isEqualySbypSgF
+ _$s7Moments16MOConfigSnapshotC7isEqualySbypSgFTo
+ _$s7Moments16MOConfigSnapshotCACycfC
+ _$s7Moments16MOConfigSnapshotCACycfc
+ _$s7Moments16MOConfigSnapshotCACycfcTo
+ _$s7Moments16MOConfigSnapshotCMF
+ _$s7Moments16MOConfigSnapshotCMa
+ _$s7Moments16MOConfigSnapshotCMf
+ _$s7Moments16MOConfigSnapshotCMn
+ _$s7Moments16MOConfigSnapshotCMo
+ _$s7Moments16MOConfigSnapshotCMu
+ _$s7Moments16MOConfigSnapshotCN
+ _$s7Moments16MOConfigSnapshotCfD
+ _$sSd9hashValueSivg
+ _$sypSgMR
+ _$sypSgMd
+ _$sypSgWOc
+ _$sypSgWOh
+ _MOEventBundleSubTypeStringDwellAtHome
+ _MOEventBundleSubTypeStringDwellAtHomeSummary
+ _OBJC_CLASS_$_MOConfigSnapshot
+ _OBJC_METACLASS_$_MOConfigSnapshot
+ __CLASS_METHODS_MOConfigSnapshot
+ __CLASS_PROPERTIES_MOConfigSnapshot
+ __DATA_MOConfigSnapshot
+ __INSTANCE_METHODS_MOConfigSnapshot
+ __IVARS_MOConfigSnapshot
+ __METACLASS_DATA_MOConfigSnapshot
+ __OBJC_$_CLASS_METHODS_MOFilePersistenceManager
+ __PROPERTIES_MOConfigSnapshot
+ __PROTOCOLS_MOConfigSnapshot
+ _kActionMediaMetaDataDominantBundleID
+ _kMOMediaGeneralNameValue
+ _symbolic _____ 7Moments16MOConfigSnapshotC
+ _symbolic ypSg
- -[MOPromptManager fetchMFeatureEnabledWithHandler:]
- ___51-[MOPromptManager fetchMFeatureEnabledWithHandler:]_block_invoke
- ___51-[MOPromptManager fetchMFeatureEnabledWithHandler:]_block_invoke_2
- ___block_descriptor_48_e8_32bs40bs_e20_v20?0B8"NSError"12ls32l8s40l8
CStrings:
+ "Failed to append config snapshot: %@"
+ "MOConfigSnapshot"
+ "MediaActionMetaDataDominantBundleID"
+ "Moments.MOConfigSnapshot"
+ "dwell_at_home"
+ "dwell_at_home_summary"
+ "eventRetentionSeconds"
+ "momentsConfig"
- "calling fetchMFeatureEnabled"
- "calling fetchMFeatureEnabled completed"
```
