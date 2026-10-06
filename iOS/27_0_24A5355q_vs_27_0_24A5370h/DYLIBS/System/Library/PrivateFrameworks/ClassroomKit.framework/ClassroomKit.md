## ClassroomKit

> `/System/Library/PrivateFrameworks/ClassroomKit.framework/ClassroomKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x26898` | `0x26978` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x8e20` | `0x8ec0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x89dc` | `0x8a75` | **`+0x99`** |
| `__TEXT.__text` | `0xb1184` | `0xb1218` | **`+0x94`** |
| `__TEXT.__objc_methlist` | `0x12bfc` | `0x12c8c` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x6f90` | `0x6fe0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e80` | `0x6eb0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2988` | `0x2998` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xef8` | `0xf00` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xbe8` | `0xbf0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x124c` | `0x1250` | **`+0x4`** |

### Other Changes

```diff

-137.0.0.0.0
+139.0.0.0.0

-  Functions: 6354
-  Symbols:   12250
-  CStrings:  1619
+  Functions: 6365
+  Symbols:   12271
+  CStrings:  1624
Symbols:
+ +[CRKOpenURLsRequest supportsSecureCoding]
+ +[CRKToolCommand printsAACTransitionDurations]
+ -[CRKOpenURLsRequest .cxx_destruct]
+ -[CRKOpenURLsRequest URLs]
+ -[CRKOpenURLsRequest encodeWithCoder:]
+ -[CRKOpenURLsRequest initWithCoder:]
+ -[CRKOpenURLsRequest setURLs:]
+ -[CRKToolCommand aacDidTransition:]
+ -[CRKToolCommand subscribeForNotifications]
+ -[CRKToolCommand unsubscribeFromNotifications]
+ _CRKAppLockAACDidTransitionNotificationName
+ _CRKAppLockAACTransitionDurationSecondsUserInfoKey
+ _CRKGuidedBrowsingContentNavigationFilterIsValid
+ _OBJC_CLASS_$_CRKOpenURLsRequest
+ _OBJC_IVAR_$_CRKOpenURLsRequest._URLs
+ _OBJC_METACLASS_$_CRKOpenURLsRequest
+ __OBJC_$_CLASS_METHODS_CRKOpenURLsRequest
+ __OBJC_$_INSTANCE_METHODS_CRKOpenURLsRequest
+ __OBJC_$_INSTANCE_VARIABLES_CRKOpenURLsRequest
+ __OBJC_$_PROP_LIST_CRKOpenURLsRequest
+ __OBJC_CLASS_RO_$_CRKOpenURLsRequest
+ __OBJC_METACLASS_RO_$_CRKOpenURLsRequest
- GCC_except_table11
CStrings:
+ "CRKAppLockAACDidTransitionNotificationName"
+ "URLs"
+ "aac_transition_seconds: %.3f"
+ "kCRKAppLockAACTransitionDurationSecondsKey"
+ "{\"aac_transition_seconds\": %.3f}"
```
