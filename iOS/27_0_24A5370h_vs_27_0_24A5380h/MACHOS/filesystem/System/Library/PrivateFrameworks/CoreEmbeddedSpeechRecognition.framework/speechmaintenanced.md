## speechmaintenanced

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/speechmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d848` | `0x3ee2c` | **`+0x15e4`** |
| `__TEXT.__oslogstring` | `0x224e` | `0x247e` | **`+0x230`** |
| `__TEXT.__swift5_capture` | `0x40c` | `0x470` | **`+0x64`** |
| `__TEXT.__eh_frame` | `0x20e0` | `0x2140` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xf58` | `0xfa8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x3d5` | `0x3b5` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2e0` | `0x2c8` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x1770` | `0x1780` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0xde1` | `0xdf1` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa10` | `0xa20` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x368` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xbc0` | `0xbc8` | **`+0x8`** |
| `__TEXT.__const` | `0xbf8` | `0xc00` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x4d0` | `0x4d8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x150` | `0x154` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xb4` | `0xb8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 638
-  Symbols:   547
-  CStrings:  366
+  Functions: 644
+  Symbols:   545
+  CStrings:  375
Symbols:
+ _$s10Foundation6LocaleV10identifierACSS_tcfC
+ _$s10Foundation6LocaleVMa
+ _$s6Speech12NCBVQProfileC12isCompatible25withCurrentAssetForLocaleSb10Foundation0I0V_tKFTj
+ _SFDeviceSupportsIFP
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ _os_transaction_create
+ _swift_retain_x28
- _$sSS18_fromUTF8RepairingySS6result_Sb11repairsMadetSRys5UInt8VGFZ
- _$sSSSTsWP
- _$sSSs25LosslessStringConvertiblesWP
- _$sSSySSxcs25LosslessStringConvertibleRzSTRzSJ7ElementSTRtzlufC
- _$sSa28_allocateBufferUninitialized15minimumCapacitys06_ArrayB0VyxGSi_tFZ
- _$ss4Int8VN
- _confstr
- _realpath$DARWIN_EXTSN
- _swift_retain_x9
- _swift_willThrowTypedImpl
CStrings:
+ "%s entity allocation cancelled."
+ "Allocation was cancelled."
+ "Asset has changed since last NCBVQ profile build; triggering full rebuild."
+ "Failed to check asset compatibility, defaulting to full rebuild: %@"
+ "Failed to perform daily NCBVQ profile maintenance: %@"
+ "Full NCBVQ profile rebuild skipped: device does not support IFP."
+ "Full NCBVQ profile rebuild skipped: feature flag is disabled."
+ "Ranking was cancelled."
+ "Task cancelled before entity tagger build. Skipping ASR and NL tagger configuration."
+ "com.apple.siri.bg_system_task.daily-ncbvq-profile-maintenance"
+ "ncbvqCascadeSetChangeListener"
+ "temporaryDirectory"
- "Sandbox: confstr(_CS_DARWIN_USER_TEMP_DIR) failed"
- "cascadeSetChangeListener"
- "com.apple.speechmaintenanced"
```
