## AppManagedFeaturesUI

> `/System/Library/PrivateFrameworks/AppManagedFeaturesUI.framework/AppManagedFeaturesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25d5c` | `0x21e80` | **`-0x3edc`** |
| `__TEXT.__eh_frame` | `0x1738` | `0x12a0` | **`-0x498`** |
| `__AUTH.__data` | `0x6e8` | `0x558` | **`-0x190`** |
| `__TEXT.__const` | `0x1358` | `0x11d8` | **`-0x180`** |
| `__TEXT.__unwind_info` | `0xaf8` | `0x998` | **`-0x160`** |
| `__TEXT.__constg_swiftt` | `0x968` | `0x818` | **`-0x150`** |
| `__DATA_CONST.__const` | `0x170` | `0xe0` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x902` | `0x87e` | **`-0x84`** |
| `__TEXT.__swift_as_cont` | `0x160` | `0xf8` | **`-0x68`** |
| `__TEXT.__swift5_reflstr` | `0x431` | `0x3d8` | **`-0x59`** |
| `__DATA.__data` | `0x788` | `0x738` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0xdf0` | `0xe38` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x8b8` | `0x878` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0xaa8` | `0xae0` | **`+0x38`** |
| `__DATA.__bss` | `0xd10` | `0xd40` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x11ae` | `0x1180` | **`-0x2e`** |
| `__TEXT.__cstring` | `0xb11` | `0xb21` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x360` | `0x370` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x4e4` | `0x4dc` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x64` | `0x68` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x68` | `0x6c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x64` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x68` | **`-0x4`** |

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

+  - /usr/lib/swift/libswiftObservation.dylib

-  Functions: 805
-  Symbols:   516
-  CStrings:  101
+  Functions: 672
+  Symbols:   515
+  CStrings:  98
Symbols:
+ __DATA__TtC20AppManagedFeaturesUI23ManagementProviderStore
+ __IVARS__TtC20AppManagedFeaturesUI23ManagementProviderStore
+ __METACLASS_DATA__TtC20AppManagedFeaturesUI23ManagementProviderStore
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s7SwiftUI14EnvironmentKeyP
+ _symbolic _____ 11Observation0A9RegistrarV
+ _symbolic _____ 20AppManagedFeaturesUI23ManagementProviderStoreC
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV018AppManagedFeaturesB0E29__Key_managementProviderStore33_DD6CAF7FCEB0DBBD934118B9F1DE7C81LLV
+ _symbolic _____SgXw 20AppManagedFeaturesUI23ManagementProviderStoreC
+ _symbolic _____SgXwz_Xx 20AppManagedFeaturesUI23ManagementProviderStoreC
- __DATA__TtC20AppManagedFeaturesUI25ConfigurationDataProvider
- __IVARS__TtC20AppManagedFeaturesUI25ConfigurationDataProvider
- __METACLASS_DATA__TtC20AppManagedFeaturesUI25ConfigurationDataProvider
- _associated conformance 20AppManagedFeaturesUI25ConfigurationDataProviderC7Combine16ObservableObjectAA0J19WillChangePublisherAdEP_AD0M0
- _os_variant_allows_internal_security_policies
- _symbolic _____ 20AppManagedFeaturesUI25ConfigurationDataProviderC
- _symbolic _____ySSG 7Combine9PublishedV
- _symbolic _____ySSSgG 7Combine9PublishedV
- _symbolic _____ySSSg_G 7Combine9PublishedV9PublisherV
- _symbolic _____ySS_G 7Combine9PublishedV9PublisherV
- _symbolic _____y_____G 7Combine9PublishedV s6UInt64V
- _symbolic _____y_____SgG 7Combine9PublishedV 18AppManagedFeatures18ManagementProviderV
- _symbolic _____y_____Sg_G 7Combine9PublishedV9PublisherV 18AppManagedFeatures18ManagementProviderV
- _symbolic _____y______G 7Combine9PublishedV9PublisherV s6UInt64V
CStrings:
+ " may require and install software updates to address critical issues and device security. \n\nThis app below cannot be removed while your device is under contract."
+ " may require and install software updates to address critical issues and device security. \n\nThis app below cannot be removed while your device is under contract. You may remove the preferred payment app at any time."
+ "AppManagedFeaturesUI/ManagementProviderStore.swift"
- " may require and install software updates to address critical issues and device security. \n\nThis app cannot be removed while your device is under contract."
- " may require and install software updates to address critical issues and device security. \n\nThis app cannot be removed while your device is under contract. You may remove the preferred payment app at any time."
- "AppManagedFeaturesUI/ConfigurationDataProvider.swift"
- "Failed to load archived provider: %{public}@"
- "Loaded archived managementProvider"
- "No archived managementProvider found"
```
