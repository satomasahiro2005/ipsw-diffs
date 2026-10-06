## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a9488` | `0x3aab74` | **`+0x16ec`** |
| `__AUTH_CONST.__objc_const` | `0x3cdf0` | `0x3d120` | **`+0x330`** |
| `__DATA.__bss` | `0x41150` | `0x41450` | **`+0x300`** |
| `__TEXT.__const` | `0x26544` | `0x266f4` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0x152fc` | `0x154ac` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0xc703` | `0xc89b` | **`+0x198`** |
| `__TEXT.__cstring` | `0x3ba15` | `0x3bb15` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x137e0` | `0x138a0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0xf538` | `0xf5f0` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x9aa6` | `0x9b58` | **`+0xb2`** |
| `__DATA_CONST.__objc_selrefs` | `0x9c08` | `0x9ca8` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x4902` | `0x4992` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x1d050` | `0x1d0d0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x35f8` | `0x3658` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x13b0` | `0x1410` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x105dc` | `0x10634` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x3f10` | `0x3f60` | **`+0x50`** |
| `__DATA.__data` | `0xd4b8` | `0xd4f0` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x25bc` | `0x25e8` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x1410` | `0x1438` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x84d0` | `0x84ec` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x7fa8` | `0x7fc4` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x7b10` | `0x7b28` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x2018` | `0x2030` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2cb8` | `0x2cc0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x9e8` | `0x9f0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xacc` | `0xad0` | **`+0x4`** |

### Other Changes

```diff

-2131.20.71.0.0
+2131.21.21.0.0

-  Functions: 25391
-  Symbols:   20645
-  CStrings:  9041
+  Functions: 25459
+  Symbols:   20713
+  CStrings:  9056
Symbols:
+ +[SFCollaborationRouteEvent eventName]
+ +[SFCollaborationRouteEvent routeCodeForActivityType:]
+ -[NSURL(Sharing) sf_hasSchemeIn:]
+ -[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]
+ -[SFAutoUnlockManager _releasePairingContextForDevice:]
+ -[SFAutoUnlockManager enableAutoUnlockWithDevice:passcodeRef:]
+ -[SFAutoUnlockManager pairingLAContexts]
+ -[SFCollaborationPerformer _submitRouteEventIfNeededWithOutcome:error:]
+ -[SFCollaborationPerformer _suppressRouteEvent]
+ -[SFCollaborationPerformer dealloc]
+ -[SFCollaborationPerformer didReportRouteEvent]
+ -[SFCollaborationPerformer performStartTicks]
+ -[SFCollaborationPerformer reportCreationFailureWithError:]
+ -[SFCollaborationPerformer routeItemType]
+ -[SFCollaborationPerformer setDidReportRouteEvent:]
+ -[SFCollaborationPerformer setPerformStartTicks:]
+ -[SFCollaborationPerformer setRouteItemType:]
+ -[SFCollaborationRouteEvent .cxx_destruct]
+ -[SFCollaborationRouteEvent activityType]
+ -[SFCollaborationRouteEvent errorCode]
+ -[SFCollaborationRouteEvent errorDomain]
+ -[SFCollaborationRouteEvent eventPayload]
+ -[SFCollaborationRouteEvent hostAppBundleID]
+ -[SFCollaborationRouteEvent itemType]
+ -[SFCollaborationRouteEvent outcome]
+ -[SFCollaborationRouteEvent setActivityType:]
+ -[SFCollaborationRouteEvent setErrorCode:]
+ -[SFCollaborationRouteEvent setErrorDomain:]
+ -[SFCollaborationRouteEvent setHostAppBundleID:]
+ -[SFCollaborationRouteEvent setItemType:]
+ -[SFCollaborationRouteEvent setOutcome:]
+ -[SFCollaborationRouteEvent setWaitMs:]
+ -[SFCollaborationRouteEvent submitEvent]
+ -[SFCollaborationRouteEvent waitMs]
+ GCC_except_table52
+ GCC_except_table62
+ GCC_except_table72
+ _OBJC_CLASS_$_SFCollaborationRouteEvent
+ _OBJC_IVAR_$_SFAutoUnlockManager._pairingLAContexts
+ _OBJC_IVAR_$_SFCollaborationPerformer._didReportRouteEvent
+ _OBJC_IVAR_$_SFCollaborationPerformer._performStartTicks
+ _OBJC_IVAR_$_SFCollaborationPerformer._routeItemType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._activityType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._errorCode
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._errorDomain
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._hostAppBundleID
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._itemType
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._outcome
+ _OBJC_IVAR_$_SFCollaborationRouteEvent._waitMs
+ _OBJC_METACLASS_$_SFCollaborationRouteEvent
+ __OBJC_$_CLASS_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_CLASS_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_VARIABLES_SFCollaborationRouteEvent
+ __OBJC_$_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationRouteEvent
+ __OBJC_CLASS_RO_$_SFCollaborationRouteEvent
+ __OBJC_METACLASS_RO_$_SFCollaborationRouteEvent
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_2
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_3
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_4
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_5
+ __xpc_type_array
+ _associated conformance 7Sharing9URLSchemeVSHAASQ
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAA0eF4TypesADP_s01_cd7BuiltineF0
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAAs0cd23ExtendedGraphemeClusterF0
+ _associated conformance 7Sharing9URLSchemeVs33ExpressibleByUnicodeScalarLiteralAA0efG4TypesADP_s01_cd7BuiltinefG0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAA0efgH4TypesADP_s01_cd7BuiltinefgH0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0cd13UnicodeScalarH0
+ _symbolic $ss26ExpressibleByStringLiteralP
+ _symbolic $ss33ExpressibleByUnicodeScalarLiteralP
+ _symbolic $ss43ExpressibleByExtendedGraphemeClusterLiteralP
+ _symbolic _____ 7Sharing9URLSchemeV
+ _type_layout_string 7Sharing9URLSchemeV
+ _xpc_type_get_name
- GCC_except_table38
- GCC_except_table65
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_2
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_3
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_4
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_5
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_6
CStrings:
+ "### Ignoring CLI mode / forced PIN from unauthenticated PreAuth on non-internal build\n"
+ "Handing off to Manage Share, not reporting a collaboration route"
+ "MusicHandoffScan"
+ "QUICHTTPPerf server is internal-only; refusing to start listener on a customer build"
+ "QUICHTTPPerf server is not available on this build"
+ "Report collaboration route: %{public}@"
+ "com.apple.sharing.collaborationRoute"
+ "createSFNodeKindsFromXPCArray: expected an XPC array, got %{public}s"
+ "createSFNodeKindsFromXPCArray: skipping unknown kind %ld at array index %ld"
+ "getSFNodeKindForIndex: index %ld out of range (count %ld)"
+ "iPhoneDuo"
+ "itemType"
+ "outcome"
+ "route"
+ "waitMs"
```
