## ScreenTimeSettingsShield

> `/Applications/ScreenTimeSettingsShield.app/ScreenTimeSettingsShield`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a1c8` | `0x1bca8` | **`+0x1ae0`** |
| `__TEXT.__oslogstring` | `0x914` | `0xb44` | **`+0x230`** |
| `__TEXT.__const` | `0xbf4` | `0xcf4` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x6c0` | `0x7a8` | **`+0xe8`** |
| `__TEXT.__constg_swiftt` | `0x618` | `0x6ec` | **`+0xd4`** |
| `__DATA.__data` | `0xba0` | `0xc68` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x14e0` | `0x15a0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x1617` | `0x16d7` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x3a0` | `0x450` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x103e` | `0x10cc` | **`+0x8e`** |
| `__TEXT.__objc_methlist` | `0x6f0` | `0x770` | **`+0x80`** |
| `__DATA.__objc_const` | `0x990` | `0x9f8` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0xa78` | `0xad8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x3a0` | `0x400` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x510` | `0x560` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x2a8` | `0x2f4` | **`+0x4c`** |
| `__DATA_CONST.__auth_ptr` | `0x410` | `0x458` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x4c8` | `0x508` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x238` | `0x268` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xcc0` | `0xceb` | **`+0x2b`** |
| `__TEXT.__cstring` | `0x52a` | `0x54a` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x217` | `0x237` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2d0` | `0x2e8` | **`+0x18`** |
| `__DATA.__common` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x48` | `0x54` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x8` | `0xc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-91.1.0.0.0
+97.0.100.2.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 398
-  Symbols:   554
-  CStrings:  347
+  Functions: 428
+  Symbols:   574
+  CStrings:  366
Symbols:
+ _$s26ScreenTimeSettingsServices0abC0C19ContentRestrictionsV17RatingRestrictionV8rawValueAGSgSi_tcfC
+ _$s26ScreenTimeSettingsServices0abC0C19ContentRestrictionsV17RatingRestrictionVMn
+ _$s26ScreenTimeSettingsServices0abC0C28regulatoryPresentationPolicyAA10RegulatoryO0fG0Vvg
+ _$s26ScreenTimeSettingsServices10RegulatoryO18PresentationPolicyV26appRatingExceptionsAllowedSbvg
+ _$s26ScreenTimeSettingsServices10RegulatoryO18PresentationPolicyVMa
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfCTq
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfc
+ _$s7SwiftUI19UIHostingControllerC8rootViewACyxGx_tcfCTq
+ _$s7SwiftUI4ViewPAAE19allowsSecureDrawingQryF
+ _$s7SwiftUI4ViewPAAE19allowsSecureDrawingQryFQOMQ
+ _MCFeatureMaximumAppsRating
+ _MKBGetDeviceLockState
+ _OBJC_CLASS_$_MCProfileConnection
+ _OBJC_METACLASS_$_UIWindow
+ _objc_release_x9
+ _objc_retain_x27
+ _swift_allocateGenericClassMetadata
+ _swift_bridgeObjectRelease_n
+ _swift_initClassMetadata2
+ _swift_isaMask
+ _swift_makeBoxUnique
- _$s26ScreenTimeSettingsServices0abC0C19ContentRestrictionsV17RatingRestrictionV6policyAGSi_tcfC
CStrings:
+ "@48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "Enforced app rating %{public}ld is outside the supported policy range"
+ "Failed to compute rating label. Rank %{public}llu is outside the supported policy range"
+ "No ManagedConfiguration connection; cannot read the enforced app rating"
+ "No effective value for MCFeatureMaximumAppsRating"
+ "No enforced app rating and the user is not migrated. Cannot describe the user's app rating"
+ "No enforced app rating. Falling back to the stored ScreenTimeSettings value"
+ "Using hardcoded itemID %{public}llu for: %{private}s"
+ "_TtC24ScreenTimeSettingsShield12SecureWindow"
+ "_canShowWhileLocked"
+ "_isSecure"
+ "_isSecureForRemoteViewService"
+ "com.apple.mobilesafari"
+ "effectiveValueForSetting:"
+ "enforcedAppRatingProvider"
+ "initWithCoder:"
+ "initWithFrame:"
+ "integerValue"
+ "sharedConnection"
```
