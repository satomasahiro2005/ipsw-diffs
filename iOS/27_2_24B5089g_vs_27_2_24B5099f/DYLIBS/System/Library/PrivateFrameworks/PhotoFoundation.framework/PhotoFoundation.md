## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240e8` | `0x24adc` | **`+0x9f4`** |
| `__AUTH_CONST.__objc_const` | `0x2828` | `0x2c38` | **`+0x410`** |
| `__TEXT.__cstring` | `0x118f` | `0x1360` | **`+0x1d1`** |
| `__TEXT.__objc_methlist` | `0xd1c` | `0xea4` | **`+0x188`** |
| `__TEXT.__lazy_helpers` | `—` | `0x150` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d0` | `0xa00` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0xdc0` | `0xec0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x863` | `0x95f` | **`+0xfc`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA.__objc_ivar` | `0x118` | `0x154` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x2e0` | `0x310` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xdd0` | `0xdf0` | **`+0x20`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__const` | `0x22e8` | `0x2300` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xf8` | `0x108` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xe48` | `0xe50` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x420` | `0x428` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA.__data` | `0x928` | `0x92c` | **`+0x4`** |

### Other Changes

```diff

-916.45.110.0.0
+916.51.202.0.0

-  Functions: 1497
-  Symbols:   1353
-  CStrings:  252
+  Functions: 1531
+  Symbols:   1431
+  CStrings:  267
Symbols:
+ -[PFRadarComponent .cxx_destruct]
+ -[PFRadarComponent description]
+ -[PFRadarComponent identifier]
+ -[PFRadarComponent initWithIdentifier:name:version:]
+ -[PFRadarComponent name]
+ -[PFRadarComponent version]
+ -[PFTapToRadarDraft .cxx_destruct]
+ -[PFTapToRadarDraft attachments]
+ -[PFTapToRadarDraft capturesPerformanceTrace]
+ -[PFTapToRadarDraft classification]
+ -[PFTapToRadarDraft component]
+ -[PFTapToRadarDraft diagnosticExtensionIdentifiers]
+ -[PFTapToRadarDraft diagnosticExtensionParameters]
+ -[PFTapToRadarDraft displayReason]
+ -[PFTapToRadarDraft isUserInitiated]
+ -[PFTapToRadarDraft problemDescription]
+ -[PFTapToRadarDraft processName]
+ -[PFTapToRadarDraft remoteDeviceClasses]
+ -[PFTapToRadarDraft setAttachments:]
+ -[PFTapToRadarDraft setCapturesPerformanceTrace:]
+ -[PFTapToRadarDraft setClassification:]
+ -[PFTapToRadarDraft setComponent:]
+ -[PFTapToRadarDraft setDiagnosticExtensionIdentifiers:]
+ -[PFTapToRadarDraft setDiagnosticExtensionParameters:]
+ -[PFTapToRadarDraft setDisplayReason:]
+ -[PFTapToRadarDraft setProblemDescription:]
+ -[PFTapToRadarDraft setProcessName:]
+ -[PFTapToRadarDraft setRemoteDeviceClasses:]
+ -[PFTapToRadarDraft setTitle:]
+ -[PFTapToRadarDraft setUserInitiated:]
+ -[PFTapToRadarDraft title]
+ GCC_except_table343
+ GCC_except_table347
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$_NSError
+ _OBJC_CLASS_$_PFRadarComponent
+ _OBJC_CLASS_$_PFTapToRadarDraft
+ _OBJC_CLASS_$_RadarComponent
+ _OBJC_CLASS_$_RadarComponent$lazyGOT
+ _OBJC_CLASS_$_RadarComponent$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_RadarDraft
+ _OBJC_CLASS_$_RadarDraft$lazyGOT
+ _OBJC_CLASS_$_RadarDraft$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_TapToRadarService
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT$loadHelper_x20
+ _OBJC_CLASS_$_TapToRadarService$lazyGOT$loadHelper_x26
+ _OBJC_IVAR_$_PFRadarComponent._identifier
+ _OBJC_IVAR_$_PFRadarComponent._name
+ _OBJC_IVAR_$_PFRadarComponent._version
+ _OBJC_IVAR_$_PFTapToRadarDraft._attachments
+ _OBJC_IVAR_$_PFTapToRadarDraft._capturesPerformanceTrace
+ _OBJC_IVAR_$_PFTapToRadarDraft._classification
+ _OBJC_IVAR_$_PFTapToRadarDraft._component
+ _OBJC_IVAR_$_PFTapToRadarDraft._diagnosticExtensionIdentifiers
+ _OBJC_IVAR_$_PFTapToRadarDraft._diagnosticExtensionParameters
+ _OBJC_IVAR_$_PFTapToRadarDraft._displayReason
+ _OBJC_IVAR_$_PFTapToRadarDraft._problemDescription
+ _OBJC_IVAR_$_PFTapToRadarDraft._processName
+ _OBJC_IVAR_$_PFTapToRadarDraft._remoteDeviceClasses
+ _OBJC_IVAR_$_PFTapToRadarDraft._title
+ _OBJC_IVAR_$_PFTapToRadarDraft._userInitiated
+ _OBJC_METACLASS_$_PFRadarComponent
+ _OBJC_METACLASS_$_PFTapToRadarDraft
+ _PFTapToRadarCreateDraft
+ _PFTapToRadarErrorDomain
+ _PFTapToRadarGetAuthorizationStatus
+ _PFTapToRadarReportUnavailable
+ __OBJC_$_INSTANCE_METHODS_PFRadarComponent
+ __OBJC_$_INSTANCE_METHODS_PFTapToRadarDraft
+ __OBJC_$_INSTANCE_VARIABLES_PFRadarComponent
+ __OBJC_$_INSTANCE_VARIABLES_PFTapToRadarDraft
+ __OBJC_$_PROP_LIST_PFRadarComponent
+ __OBJC_$_PROP_LIST_PFTapToRadarDraft
+ __OBJC_CLASS_RO_$_PFRadarComponent
+ __OBJC_CLASS_RO_$_PFTapToRadarDraft
+ __OBJC_METACLASS_RO_$_PFRadarComponent
+ __OBJC_METACLASS_RO_$_PFTapToRadarDraft
+ ___PFTapToRadarGetAuthorizationStatus_block_invoke
+ ___block_descriptor_40_e8_32bs_e35_v16?0"TapToRadarServiceSettings"8ls32l8
+ __dyld_lazy_load
+ _lazyLoadFlag$TapToRadarKit
+ _objc_opt_new
+ _objc_setProperty_nonatomic_copy
- GCC_except_table308
- GCC_except_table312
- _PFGetHeapStatistics
- _mach_task_self_
- _malloc_get_all_zones
- _malloc_zone_statistics
CStrings:
+ "<%@: %p; %ld: %@ | %@>"
+ "BOOL PFTapToRadarCreateDraft(PFTapToRadarDraft *__strong _Nonnull, NSError *__autoreleasing * _Nullable)"
+ "Not creating Tap-to-Radar draft '%{public}@': %{public}@"
+ "PFTapToRadar.m"
+ "PFTapToRadarErrorDomain"
+ "Refusing user initiated Tap-to-Radar draft '%{public}@': authorization status %ld"
+ "Tap-to-Radar is gathering diagnostics for draft '%{public}@'"
+ "Tap-to-Radar refused draft '%{public}@': %{public}@"
+ "TapToRadarKit is not installed"
+ "completionHandler != nil"
+ "draft != nil"
+ "the user or Tap-to-Radar withheld permission for this process"
+ "this is a customer install"
+ "v16@?0@\"TapToRadarServiceSettings\"8"
+ "void PFTapToRadarGetAuthorizationStatus(void (^__strong _Nonnull)(PFTapToRadarAuthorizationStatus))"
```
