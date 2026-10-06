## TeaUI

> `/System/Library/PrivateFrameworks/TeaUI.framework/TeaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x369dc0` | `0x36d498` | **`+0x36d8`** |
| `__AUTH_CONST.__const` | `0x2d738` | `0x2dd98` | **`+0x660`** |
| `__AUTH_CONST.__objc_const` | `0x1bee0` | `0x1c200` | **`+0x320`** |
| `__TEXT.__objc_methlist` | `0x8448` | `0x8760` | **`+0x318`** |
| `__TEXT.__swift5_capture` | `0x9148` | `0x93e4` | **`+0x29c`** |
| `__DATA_CONST.__objc_selrefs` | `0x46c8` | `0x4880` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x3ab5` | `0x3bf5` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x11088` | `0x111a0` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0x13d5c` | `0x13e5c` | **`+0x100`** |
| `__DATA.__data` | `0x5fb0` | `0x60a0` | **`+0xf0`** |
| `__TEXT.__const` | `0x283d4` | `0x284c4` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0xda6a` | `0xdb44` | **`+0xda`** |
| `__TEXT.__swift5_fieldmd` | `0xfaa0` | `0xfb78` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0xd02f` | `0xd0ff` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x45c8` | `0x4688` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x9d01` | `0x9dc1` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x9c10` | `0x9ca8` | **`+0x98`** |
| `__DATA_DIRTY.__data` | `0x11588` | `0x11548` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x25b0` | `0x25e0` | **`+0x30`** |
| `__AUTH.__data` | `0x2400` | `0x2420` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2e20` | `0x2e40` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x3f0` | `0x400` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1a60` | `0x1a68` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb90` | `0xb98` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x5ce8` | `0x5cf0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1170` | `0x1178` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x548` | `0x54c` | **`+0x4`** |

### Other Changes

```diff

-1478.1.0.0.0
+1510.0.0.0.0

-  Functions: 31920
-  Symbols:   8273
-  CStrings:  1111
+  Functions: 32083
+  Symbols:   8294
+  CStrings:  1117
Symbols:
+ _OBJC_CLASS_$_TSApplicationBackgroundFetchScheduler
+ _OBJC_METACLASS_$_TSApplicationBackgroundFetchScheduler
+ __DATA_TSApplicationBackgroundFetchScheduler
+ __INSTANCE_METHODS_TSApplicationBackgroundFetchScheduler
+ __IVARS_TSApplicationBackgroundFetchScheduler
+ __METACLASS_DATA_TSApplicationBackgroundFetchScheduler
+ __OBJC_$_PROP_LIST_UIApplicationDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIApplicationDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIApplicationDelegate
+ __OBJC_$_PROTOCOL_REFS_UIApplicationDelegate
+ __OBJC_LABEL_PROTOCOL_$_UIApplicationDelegate
+ __OBJC_PROTOCOL_$_UIApplicationDelegate
+ __PROTOCOLS_TSApplicationBackgroundFetchScheduler
+ ___swift_closure_destructor.20Tm
+ ___swift_get_extra_inhabitant_indexTm
+ ___swift_store_extra_inhabitant_indexTm
+ ___unnamed_28
+ ___unnamed_32
+ ___unnamed_36
+ ___unnamed_43
+ _flat unique So21UIApplicationDelegate_p
+ _symbolic $s5TeaUI29MastheadSearchCoordinatorTypeP
+ _symbolic _____ 5TeaUI25BlueprintStagedImpressionV
+ _symbolic _____ 5TeaUI35ApplicationBackgroundFetchSchedulerC
+ _symbolic __________yxq_G_AAtc 12CoreGraphics7CGFloatV 5TeaUI25BlueprintStagedImpressionV
+ _symbolic ______p So21UIApplicationDelegateP
+ _symbolic ______pSgXw 5TeaUI29MastheadSearchCoordinatorTypeP
+ _symbolic _____yxGSgXw 5TeaUI26BlueprintImpressionManagerC
+ _symbolic _____yxGSgXwz_x______RzlXX 5TeaUI26BlueprintImpressionManagerC AA0C12ProviderTypeP
+ _symbolic y_____yxG______y10Descriptor_____Qz5ModelAEQzGtc 5TeaUI26BlueprintImpressionManagerC AA0c6StagedD0V AA0C12ProviderTypeP
- ___swift_closure_destructor.16Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.52Tm
- ___swift_memcpy290_8
- ___swift_memcpy392_8
- ___unnamed_27
- ___unnamed_29
- ___unnamed_33
- ___unnamed_40
CStrings:
+ "Card with view controller %@ is hidden, deferring behavior update until it is presented again"
+ "Exceeded the maximum navigation depth of <%{public}d> navigating to activity <%{public}@>; a router is re-entering the navigator"
+ "Ignoring restore state %s for card with view controller: %@"
+ "Setting restore state %s for card with view controller: %@"
+ "TeaUI.ApplicationBackgroundFetchScheduler"
+ "Unable to set the restore state for view controller %s, no matching card item found"
```
