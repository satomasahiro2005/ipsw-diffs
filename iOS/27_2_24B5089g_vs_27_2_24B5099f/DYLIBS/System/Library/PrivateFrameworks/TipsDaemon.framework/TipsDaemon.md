## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0658` | `0xa1664` | **`+0x100c`** |
| `__AUTH_CONST.__objc_const` | `0x80f8` | `0x82a8` | **`+0x1b0`** |
| `__AUTH.__objc_data` | `0xf00` | `0x1020` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x38b8` | `0x3968` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x427c` | `0x430c` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x66e` | `0x6ce` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d88` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0x4cd8` | `0x4d20` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x988` | `0x9c8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xeac` | `0xee8` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x1eb0` | `0x1ee0` | **`+0x30`** |
| `__TEXT.__const` | `0x3258` | `0x3288` | **`+0x30`** |
| `__AUTH.__data` | `0x50` | `0x78` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2838` | `0x2860` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2a00` | `0x2a20` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2698` | `0x26b8` | **`+0x20`** |
| `__DATA.__data` | `0x8a8` | `0x8b8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x540` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1d10` | `0x1d20` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x740` | `0x750` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd20` | `0xd18` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x3420` | `0x3428` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x117a` | `0x1180` | **`+0x6`** |
| `__DATA.__objc_ivar` | `0x220` | `0x224` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x114` | `0x118` | **`+0x4`** |

### Other Changes

```diff

-866.2.2.0.0
+866.2.3.0.0

-  Functions: 3317
-  Symbols:   3460
-  CStrings:  809
+  Functions: 3348
+  Symbols:   3483
+  CStrings:  813
Symbols:
+ -[TPSBundleIdsCondition .cxx_destruct]
+ -[TPSBundleIdsCondition init]
+ -[TPSBundleIdsCondition requestingBundleId]
+ -[TPSBundleIdsCondition setRequestingBundleId:]
+ -[TPSBundleIdsCondition targetingValidations]
+ -[TPSDeliveryPrecondition applyRequestingBundleId:]
+ -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]
+ -[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]
+ _OBJC_CLASS_$_TPSBundleIdsCondition
+ _OBJC_CLASS_$_TPSBundleIdsValidation
+ _OBJC_IVAR_$_TPSBundleIdsCondition._requestingBundleId
+ _OBJC_METACLASS_$_TPSBundleIdsCondition
+ _OBJC_METACLASS_$_TPSBundleIdsValidation
+ __DATA_TPSBundleIdsValidation
+ __INSTANCE_METHODS_TPSBundleIdsValidation
+ __IVARS_TPSBundleIdsValidation
+ __METACLASS_DATA_TPSBundleIdsValidation
+ __OBJC_$_INSTANCE_METHODS_TPSBundleIdsCondition
+ __OBJC_$_INSTANCE_VARIABLES_TPSBundleIdsCondition
+ __OBJC_$_PROP_LIST_TPSBundleIdsCondition
+ __OBJC_CLASS_RO_$_TPSBundleIdsCondition
+ __OBJC_METACLASS_RO_$_TPSBundleIdsCondition
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_2
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_3
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_4
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_5
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_6
+ ___45-[TPSBundleIdsCondition targetingValidations]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_2
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_3
+ ___block_descriptor_112_e8_32s40s48s56s64r72r80r88r96r104w_e24_v16?0?<v?"NSError">8lw104l8s32l8s40l8s48l8r64l8r72l8r80l8s56l8r88l8r96l8
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"TPSInclusivityInfo"8Q16^B24ls32l8s40l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80w_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8w80l8s40l8s48l8s56l8s64l8s72l8
+ _symbolic _____ 10TipsDaemon19BundleIdsValidationC
- -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]
- -[TPSTipsManager processClientConditions:targetingCache:completionHandler:]
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_2
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_3
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_4
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_5
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_6
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_2
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_3
- ___block_descriptor_104_e8_32s40s48s56r64r72r80r88r96w_e24_v16?0?<v?"NSError">8lw96l8s32l8s40l8r56l8r64l8r72l8s48l8r80l8r88l8
- ___block_descriptor_80_e8_32s40s48s56s64s72w_e39_v32?0"NSString"8"NSDictionary"16^B24lw72l8s32l8s40l8s48l8s56l8s64l8
CStrings:
+ " - checking requesting bundle id: "
+ " - no requesting bundle id; condition does not match."
+ "TipsDaemon.BundleIdsValidation"
+ "bundleIds"
```
