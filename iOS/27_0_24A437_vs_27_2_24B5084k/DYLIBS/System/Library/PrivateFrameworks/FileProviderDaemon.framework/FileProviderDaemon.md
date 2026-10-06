## FileProviderDaemon

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/FileProviderDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7d478` | `0xa82b54` | **`+0x56dc`** |
| `__TEXT.__cstring` | `0x4d705` | `0x4dd45` | **`+0x640`** |
| `__AUTH_CONST.__const` | `0x4c190` | `0x4c3f8` | **`+0x268`** |
| `__AUTH_CONST.__cfstring` | `0x7340` | `0x7540` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0x27cb8` | `0x27dd8` | **`+0x120`** |
| `__TEXT.__const` | `0x2e370` | `0x2e480` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0xd618` | `0xd70c` | **`+0xf4`** |
| `__TEXT.__swift5_capture` | `0x1a848` | `0x1a918` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6200` | `0x62c0` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x14bae` | `0x14c6e` | **`+0xc0`** |
| `__TEXT.__ustring` | `0x176e` | `0x181a` | **`+0xac`** |
| `__TEXT.__objc_methlist` | `0x98a4` | `0x9914` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x16568` | `0x165d8` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x2d248` | `0x2d2b0` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x46f8` | `0x4740` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xf8bd` | `0xf8fd` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x10e00` | `0x10e30` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1920` | `0x1940` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xbb4` | `0xbcc` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xd1a4` | `0xd1bc` | **`+0x18`** |
| `__AUTH.__data` | `0x2898` | `0x28a8` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x33b0` | `0x33c0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x14720` | `0x14710` | **`-0x10`** |

### Other Changes

```diff

-4838.0.125.0.0
+4838.40.53.502.1

-  Functions: 31526
-  Symbols:   12573
-  CStrings:  8142
+  Functions: 31574
+  Symbols:   12599
+  CStrings:  8181
Symbols:
+ -[FPDConfigurationStore hardConcurrentBackgroundDownloadLimit]
+ -[FPDConfigurationStore hardConcurrentBackgroundUploadLimit]
+ -[FPDConfigurationStore softConcurrentBackgroundDownloadLimit]
+ -[FPDConfigurationStore softConcurrentBackgroundUploadLimit]
+ -[FPDProviderDescriptor backgroundDownloadPipelineDepth]
+ -[FPDProviderDescriptor backgroundUploadPipelineDepth]
+ -[FPDProviderDescriptor setBackgroundDownloadPipelineDepth:]
+ -[FPDProviderDescriptor setBackgroundUploadPipelineDepth:]
+ -[FPDXPCServicer dumpStaleSpotlightDomainsToDumper:providerFilter:]
+ GCC_except_table274
+ GCC_except_table275
+ GCC_except_table276
+ GCC_except_table280
+ GCC_except_table284
+ GCC_except_table285
+ GCC_except_table294
+ GCC_except_table298
+ GCC_except_table300
+ GCC_except_table309
+ GCC_except_table319
+ GCC_except_table326
+ GCC_except_table328
+ GCC_except_table330
+ GCC_except_table335
+ GCC_except_table349
+ GCC_except_table375
+ GCC_except_table376
+ GCC_except_table377
+ GCC_except_table406
+ GCC_except_table431
+ GCC_except_table438
+ GCC_except_table447
+ GCC_except_table451
+ GCC_except_table452
+ GCC_except_table453
+ _FPSpotlightIndexNamePrefix
+ _OBJC_CLASS_$_CSDonationProgressFailure
+ _OBJC_CLASS_$_CSDonationProgressQueryResult
+ _OBJC_IVAR_$_FPDConfigurationStore._hardConcurrentBackgroundDownloadLimit
+ _OBJC_IVAR_$_FPDConfigurationStore._hardConcurrentBackgroundUploadLimit
+ _OBJC_IVAR_$_FPDConfigurationStore._softConcurrentBackgroundDownloadLimit
+ _OBJC_IVAR_$_FPDConfigurationStore._softConcurrentBackgroundUploadLimit
+ _OBJC_IVAR_$_FPDProviderDescriptor._backgroundDownloadPipelineDepth
+ _OBJC_IVAR_$_FPDProviderDescriptor._backgroundUploadPipelineDepth
+ ___67-[FPDXPCServicer dumpStaleSpotlightDomainsToDumper:providerFilter:]_block_invoke
+ ___67-[FPDXPCServicer dumpStaleSpotlightDomainsToDumper:providerFilter:]_block_invoke_2
+ ___block_descriptor_32_e73_q24?0"CSDonationProgressQueryResult"8"CSDonationProgressQueryResult"16l
+ ___block_descriptor_56_e8_32s40r48r_e29_v24?0"NSArray"8"NSError"16lr40l8r48l8s32l8
+ ___swift_closure_destructor.120Tm
+ ___swift_closure_destructor.137Tm
+ ___swift_closure_destructor.1767Tm
+ ___swift_closure_destructor.1865Tm
+ ___swift_closure_destructor.1893Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.57Tm
+ ___swift_closure_destructor.6647Tm
+ ___swift_closure_destructor.98Tm
+ ___unnamed_114
+ ___unnamed_115
+ _symbolic SaySo29CSDonationProgressQueryResultCGSg
+ _symbolic SaySo29CSDonationProgressQueryResultCGSgz_Xx
+ _symbolic _____XjSgSb______pSgIegnyg_ 18FileProviderDaemon26_DatabaseReadWriteAccessor_pRi0_s_XPXg s5ErrorP
- GCC_except_table272
- GCC_except_table273
- GCC_except_table277
- GCC_except_table278
- GCC_except_table279
- GCC_except_table283
- GCC_except_table287
- GCC_except_table288
- GCC_except_table297
- GCC_except_table306
- GCC_except_table307
- GCC_except_table312
- GCC_except_table322
- GCC_except_table332
- GCC_except_table334
- GCC_except_table336
- GCC_except_table338
- GCC_except_table352
- GCC_except_table378
- GCC_except_table379
- GCC_except_table380
- GCC_except_table409
- GCC_except_table437
- GCC_except_table441
- GCC_except_table450
- ___swift_closure_destructor.1765Tm
- ___swift_closure_destructor.1849Tm
- ___swift_closure_destructor.1877Tm
- ___swift_closure_destructor.32Tm
- ___swift_closure_destructor.38Tm
- ___swift_closure_destructor.44Tm
- ___swift_closure_destructor.6644Tm
- ___swift_closure_destructor.76Tm
- ___swift_closure_destructor.82Tm
- ___unnamed_116
- ___unnamed_117
CStrings:
+ "         allKnownItems: spotlight:"
+ "         allKnownItemsIsPartial: "
+ "         donatedItems: "
+ "         failure reason: "
+ "         indexedItems: <error: "
+ "         indexedItems: <timed out after 1s>\n"
+ "         indexedItems: spotlight-index:"
+ "         itemsNeedingDonation: spotlight:"
+ "         partiallyDonatedItems: "
+ "         progress type: "
+ "         redonationRequests: "
+ "         status: "
+ "         underlying error: "
+ "      + spotlight donation progress:\n"
+ "      + spotlight donation progress: <error: "
+ "      + spotlight donation progress: <none reported>\n"
+ "      + spotlight donation progress: <provider domain unavailable>\n"
+ "      + spotlight donation progress: <timed out after 1s>\n"
+ "     %@  bundle:%@"
+ "  allKnownItems:%lu"
+ "  allKnownItems:<failure reason:%lu>"
+ "  allKnownItems:<no progress reported, status:%lu>"
+ " (no progress stored)"
+ "%@⚠️  Found %lu stale spotlight domains (Spotlight tracks, FP has no live domain):%@\n"
+ "+ stale spotlight domains: <error: %@>\n"
+ "+ stale spotlight domains: <none>\n"
+ "+ stale spotlight domains: <timed out after 2s>\n"
+ "NSExtensionFileProviderBackgroundDownloadPipelineDepth"
+ "NSExtensionFileProviderBackgroundUploadPipelineDepth"
+ "_backgroundDownloadPipelineDepth"
+ "_backgroundUploadPipelineDepth"
+ "backgroundDownload"
+ "backgroundUpload"
+ "hardConcurrentBackgroundDownloadLimit"
+ "hardConcurrentBackgroundUploadLimit"
+ "kMDItemFileProviderID == \""
+ "q24@?0@\"CSDonationProgressQueryResult\"8@\"CSDonationProgressQueryResult\"16"
+ "softConcurrentBackgroundDownloadLimit"
+ "softConcurrentBackgroundUploadLimit"
```
