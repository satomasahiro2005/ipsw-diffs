## stickersd

> `/System/Library/PrivateFrameworks/Stickers.framework/Support/stickersd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22150` | `0x2601c` | **`+0x3ecc`** |
| `__TEXT.__eh_frame` | `0x115c` | `0x12f4` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0x1117` | `0x1267` | **`+0x150`** |
| `__DATA_CONST.__const` | `0xdd8` | `0xd88` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x270` | `0x2c0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x430` | `0x3f6` | **`-0x3a`** |
| `__TEXT.__const` | `0xe80` | `0xe50` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x2e4` | `0x2bc` | **`-0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x39c` | `0x3c4` | **`+0x28`** |
| `__DATA.__objc_const` | `0x990` | `0x970` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x13f0` | `0x1410` | **`+0x20`** |
| `__TEXT.__cstring` | `0x618` | `0x638` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x945` | `0x925` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x440` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x588` | `0x5a4` | **`+0x1c`** |
| `__DATA.__data` | `0x978` | `0x990` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xa08` | `0xa18` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x318` | `0x328` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x258` | `0x250` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0x98` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-90.1.2.0.0
+90.1.5.0.0

-  Functions: 523
-  Symbols:   490
-  CStrings:  280
+  Functions: 538
+  Symbols:   491
+  CStrings:  283
Symbols:
+ _$s10Foundation10CocoaErrorV4CodeV18fileReadNoSuchFileAEvgZ
+ _$s10Foundation10CocoaErrorV4CodeVMa
+ _$s10Foundation10CocoaErrorV4CodeVSQAAMc
+ _$s10Foundation10CocoaErrorVAA21_BridgedStoredNSErrorAAMc
+ _$s10Foundation10CocoaErrorVMa
+ _$s10Foundation21_BridgedStoredNSErrorPAAE4code4CodeQzvg
+ _$s8Stickers0A12SearchPolicyO13usesSpotlightSbvgZ
+ _$s8Stickers20StickerStoreProtocolP7sticker10identifier23representationSpecifierAA0B0CSg10Foundation4UUIDV_AH12FetchRequestV014RepresentationH0OtKFTj
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _objc_retain_x27
+ _swift_deallocUninitializedObject
+ _swift_release_x27
+ _swift_retain_x27
- _$sScG17makeAsyncIteratorScG0C0Vyx_GyF
- _$sScG8IteratorV4next9isolationxSgScA_pSgYi_tYaF
- _$sScG8IteratorV4next9isolationxSgScA_pSgYi_tYaFTu
- _$sScG8IteratorVMn
- _$ss12_ArrayBufferV18_typeCheckSlowPathyySiF
- _$ss13withTaskGroup2of9returning9isolation4bodyq_xm_q_mScA_pSgYiq_ScGyxGzYaXEtYas8SendableRzr0_lF
- _$ss13withTaskGroup2of9returning9isolation4bodyq_xm_q_mScA_pSgYiq_ScGyxGzYaXEtYas8SendableRzr0_lFTu
- _$ss15ContiguousArrayV034_makeUniqueAndReserveCapacityIfNotD0yyFyXl_Ts5
- _$ss15ContiguousArrayV12_endMutationyyFyXl_Ts5
- _$ss15ContiguousArrayV36_reserveCapacityAssumingUniqueBuffer8oldCountySi_tFyXl_Ts5
- _$ss15ContiguousArrayV37_appendElementAssumeUniqueAndCapacity_03newD0ySi_xntFyXl_Ts5
- _$ss18_CocoaArrayWrapperVys12_SliceBufferVyyXlGSnySiGcig
- _swift_retain_x23
CStrings:
+ "DAS cancelled indexing task; flushing progress and breaking out of sticker fetch loop"
+ "Failed to fetch sticker %s for indexing: %@"
+ "Failed to flush progress while cancelling: %@"
+ "Pruned %ld tracking entries for deleted stickers"
+ "Sticker %s left the store before it could be indexed"
+ "V2 search engine owns sticker search; not registering as a Spotlight daemon client"
+ "V2 search engine owns sticker search; not scheduling Spotlight searchText repair"
+ "sticker-indexing-progress"
- "DAS cancelled indexing task; breaking out of sticker fetch loop"
- "Loaded %ld tracked sticker UUIDs from disk"
- "Updated tracking file with %ld newly indexed stickers"
- "fileExistsAtPath:"
- "fileManager"
```
