## IntelligenceFlowShared

> `/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3338` | `0xa9034` | **`+0x5cfc`** |
| `__DATA_DIRTY.__bss` | `0xa980` | `0xc900` | **`+0x1f80`** |
| `__DATA.__bss` | `0x16600` | `0x15790` | **`-0xe70`** |
| `__DATA_DIRTY.__data` | `0x2af0` | `0x3828` | **`+0xd38`** |
| `__TEXT.__const` | `0x115e0` | `0x11ec0` | **`+0x8e0`** |
| `__DATA.__data` | `0x2630` | `0x1e38` | **`-0x7f8`** |
| `__DATA_CONST.__got` | `0x0` | `0x660` | **`+0x660`** |
| `__AUTH_CONST.__const` | `0x9120` | `0x9690` | **`+0x570`** |
| `__AUTH.__data` | `0x438` | `0x160` | **`-0x2d8`** |
| `__TEXT.__cstring` | `0x3d15` | `0x3fdb` | **`+0x2c6`** |
| `__TEXT.__swift5_fieldmd` | `0x44ac` | `0x4758` | **`+0x2ac`** |
| `__TEXT.__swift5_reflstr` | `0x33bc` | `0x35dc` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x3cd0` | `0x3ef0` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x3eb8` | `0x40b4` | **`+0x1fc`** |
| `__TEXT.__constg_swiftt` | `0x2afc` | `0x2cec` | **`+0x1f0`** |
| `__AUTH_CONST.__objc_const` | `0x760` | `0x930` | **`+0x1d0`** |
| `__TEXT.__swift5_typeref` | `0x3050` | `0x31de` | **`+0x18e`** |
| `__AUTH_CONST.__auth_got` | `0xf30` | `0x1010` | **`+0xe0`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0x288` | **`+0xa8`** |
| `__TEXT.__swift5_proto` | `0x10b0` | `0x1140` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x4fe` | `0x576` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `—` | `0x60` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x138` | `0xe0` | **`-0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x210` | `0x268` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x200` | `0x248` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x480` | `0x4b8` | **`+0x38`** |
| `__TEXT.__swift5_types` | `0x45c` | `0x488` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA.__common` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x44` | `0x4c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x3c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-3600.144.5.501.3
+3600.147.12.501.3

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 7198
-  Symbols:   204
-  CStrings:  512
+  Functions: 7418
+  Symbols:   230
+  CStrings:  537
Symbols:
+ _IFCopyBundleIdsDisabledForSiri
+ _IFResetTCCSiriExclusion
+ _IOSurfaceCreateXPCObject
+ _IOSurfaceGetID
+ _IOSurfaceLookupFromXPCObject
+ _OBJC_CLASS_$_IFTCCSiriExclusionToken
+ _OBJC_CLASS_$_NSString
+ _OBJC_METACLASS_$_IFTCCSiriExclusionToken
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ _TCCAccessResetForBundleId
+ __NSConcreteGlobalBlock
+ ___CFConstantStringClassReference
+ ___NSArray0__struct
+ __os_log_error_impl
+ __swiftEmptySetSingleton
+ _dispatch_once
+ _notify_cancel
+ _notify_check
+ _notify_register_check
+ _objc_alloc
+ _objc_claimAutoreleasedReturnValue
+ _objc_release_x1
+ _objc_retainAutorelease
+ _objc_retainAutoreleaseReturnValue
+ _os_log_create
+ _tcc_service_get_name
+ _tcc_service_singleton_for_CF_name
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "AppExclusion"
+ "AppExclusions"
+ "EnforceActionValidatorOnMultimodalRequests"
+ "ForceDialogOverrideOTAAsset"
+ "ForceSkimmerOTAAsset"
+ "InvocationContext("
+ "NativeXPCSessionMessageEncoding"
+ "bundleIdentifier"
+ "com.apple.TCC.%s.authorization.changed"
+ "com.apple.tcc.access.changed"
+ "contextMenuDataExport"
+ "contextRetrieval.fetchDirectWindow"
+ "crossDeviceLiveEntities"
+ "fetchDirectWindow"
+ "invocationContext"
+ "isAccessExcluded"
+ "kTCCServiceSiri"
+ "keyboardcandidatebar"
+ "localLiveEntities"
+ "no TCC service handle; falling back to global notification name"
+ "notify_register_check failed (status=%u) for %{public}@"
+ "roundTripTimeout"
+ "textcursoraffordance"
+ "texteditwritingtoolspanel"
+ "v8@?0"
+ "visualintelligence"
+ "writingtoolstoolbar"
- "HomePlannerTools"
- "IntercomPlannerTools"
```
