## AuthorizationPromptService

> `/Applications/AuthorizationPromptService.app/AuthorizationPromptService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1a0` | `0x1ce88` | **`+0xce8`** |
| `__TEXT.__swift5_typeref` | `0x4642` | `0x4c1c` | **`+0x5da`** |
| `__DATA.__objc_data` | `0x6d0` | `0x5a0` | **`-0x130`** |
| `__DATA.__objc_const` | `0x2680` | `0x2590` | **`-0xf0`** |
| `__TEXT.__constg_swiftt` | `0x684` | `0x5d0` | **`-0xb4`** |
| `__TEXT.__auth_stubs` | `0x1800` | `0x18a0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x820` | `0x898` | **`+0x78`** |
| `__DATA_CONST.__auth_got` | `0xc08` | `0xc58` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x367` | `0x317` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x3ca` | `0x38a` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x1bf9` | `0x1bb9` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x36c` | `0x32c` | **`-0x40`** |
| `__DATA.__data` | `0x1258` | `0x1288` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x734` | `0x704` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0xf4a` | `0xf1a` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x200` | `0x22c` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xcc0` | `0xce0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x500` | `0x510` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x478` | `0x488` | **`+0x10`** |
| `__TEXT.__const` | `0x1244` | `0x1254` | **`+0x10`** |
| `__TEXT.__cstring` | `0x13e6` | `0x13d6` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x48` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x538` | `0x530` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x48` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-903.0.0.0.0
+906.0.0.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 500
-  Symbols:   691
-  CStrings:  460
+  Functions: 498
+  Symbols:   704
+  CStrings:  454
Symbols:
+ _$s10Foundation6LocaleV12LanguageCodeV10identifierSSvg
+ _$s10Foundation6LocaleV12LanguageCodeVMa
+ _$s10Foundation6LocaleV12LanguageCodeVMn
+ _$s10Foundation6LocaleV8LanguageV12languageCodeAC0cE0VSgvg
+ _$s10Foundation6LocaleV8LanguageVMa
+ _$s10Foundation6LocaleV8languageAC8LanguageVvg
+ _$s23TCCAuthorizationService27AuthorizationResultListenerC12cancelPromptyyFTj
+ _$s23TCCAuthorizationService27AuthorizationResultListenerC18didRespondToPromptSbyFTj
+ _$s7SwiftUI26AccessibilityChildBehaviorV7containACvgZ
+ _$s7SwiftUI26AccessibilityChildBehaviorVMa
+ _$s7SwiftUI4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tF
+ _$s7SwiftUI4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOMQ
+ _MGCopyAnswer
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$_NSNumber
+ ___CFConstantStringClassReference
+ _swift_retain_x27
- _$s23TCCAuthorizationService27AuthorizationResultListenerC16promptDidDismissyyFTj
- _$sSo24UISceneConnectionOptionsC19AppRestrictionsCoreE16preflightRequestSo012ALRPreflightH0CSgvg
- _OBJC_CLASS_$_NSObject
- _OBJC_CLASS_$_UIApplication
CStrings:
+ " #TCCAuthorizationPromptService RemoteAlertManager: user did not yet respond to the prompt. Returning undetermined authorization result."
+ "alr_preflightRequest"
+ "characterDirectionForLanguage:"
+ "floatValue"
+ "main-screen-scale"
+ "requestAuthorization(forService:auditToken:forBundleId:usageDescription:includeLearnMore:completionHandler:)"
+ "requestAuthorizationForService:auditToken:forBundleId:usageDescription:includeLearnMore:completionHandler:"
+ "setSemanticContentAttribute:"
+ "v40@0:8@\"NSString\"16@\"NSData\"24@?<v@?@\"NSError\">32"
+ "v64@0:8@\"NSString\"16@\"BSAuditToken\"24@\"NSString\"32@\"NSString\"40@\"NSNumber\"48@?<v@?@\"NSNumber\"@\"NSError\">56"
- " #TCCAuthorizationPromptService RemoteAlertManager: alert activated"
- "AuthorizationPromptService.RemoteAlertManager"
- "Vv40@0:8@\"NSString\"16@\"NSData\"24@?<v@?@\"NSError\">32"
- "Vv40@0:8@16@24@?32"
- "Vv56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSNumber\"40@?<v@?@\"NSNumber\"@\"NSError\">48"
- "Vv56@0:8@16@24@32@40@?48"
- "_TtC26AuthorizationPromptService18RemoteAlertManager"
- "init()"
- "mainScreen"
- "remoteAlertHandle"
- "remoteAlertHandleDidActivate(_:)"
- "remoteAlertManager"
- "requestAuthorization(forService:forBundleId:usageDescription:includeLearnMore:completionHandler:)"
- "requestAuthorizationForService:forBundleId:usageDescription:includeLearnMore:completionHandler:"
- "sharedApplication"
- "userInterfaceLayoutDirection"
```
