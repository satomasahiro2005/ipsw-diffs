## LimitedModeShieldApp

> `/Applications/LimitedModeShieldApp.app/LimitedModeShieldApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd148` | `0xcf2c` | **`-0x21c`** |
| `__TEXT.__oslogstring` | `0x669` | `0x6f9` | **`+0x90`** |
| `__TEXT.__const` | `0x764` | `0x7b4` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x2c4` | `0x29c` | **`-0x28`** |
| `__TEXT.__cstring` | `0x5fb` | `0x61b` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x14d7` | `0x14f7` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2e0` | `0x300` | **`+0x20`** |
| `__DATA.__bss` | `0x3e8` | `0x400` | **`+0x18`** |
| `__DATA.__data` | `0x898` | `0x888` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x258` | `0x248` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0xfd0` | `0xfe0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x141` | `0x131` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x7f0` | `0x7f8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1fd0` | `0x1fd6` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

-  Functions: 231
+  Functions: 234

-  CStrings:  333
+  CStrings:  336
Symbols:
+ _$s18AppManagedFeatures0abC9ConstantsO15isInternalBuildSbvgZ
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC010managementF00abC00eF0VSgvg
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC04callF7SupportyyF
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC04longF4NameSSvg
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC04openfA0yyF
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC05shortF4NameSSvg
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC20formattedPhoneNumberyS2SF
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC23loadActiveConfigurationyyYaF
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC23loadActiveConfigurationyyYaFTu
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreC8bundleIDSSSgvg
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreCMa
+ _$s20AppManagedFeaturesUI23ManagementProviderStoreCMn
+ _$s7SwiftUI11EnvironmentVMa
+ _$s7SwiftUI11EnvironmentVMn
+ _$s7SwiftUI17EnvironmentValuesV018AppManagedFeaturesB0E23managementProviderStoreAD010ManagementiJ0Cvg
+ _$s7SwiftUI17EnvironmentValuesV018AppManagedFeaturesB0E23managementProviderStoreAD010ManagementiJ0CvpMV
+ _$s7SwiftUI17EnvironmentValuesV018AppManagedFeaturesB0E23managementProviderStoreAD010ManagementiJ0Cvs
+ _$s7SwiftUI17EnvironmentValuesVACycfC
+ _$s7SwiftUI17EnvironmentValuesVMa
+ _$s7SwiftUI3LogO013runtimeIssuesC0So9OS_os_logCvgZ
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _swift_getAtKeyPath
- _$s18AppManagedFeatures0abC9ConstantsO17BundleIdentifiersO6daemonyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO17BundleIdentifiersO8rawValueSSvg
- _$s18AppManagedFeatures0abC9ConstantsO17BundleIdentifiersOMa
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC010loadActiveE0yyYaFTjTu
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC010managementG00abC0010ManagementG0VSgvgTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC04callG7SupportyyFTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC04longG4NameSSvgTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC04opengA0yyFTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC05shortG4NameSSvgTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC20formattedPhoneNumberyS2SFTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC7Combine16ObservableObjectAAMc
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderC8bundleIDSSSgvgTj
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderCACycfc
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderCMa
- _$s20AppManagedFeaturesUI25ConfigurationDataProviderCMn
- _$s7SwiftUI11StateObjectV12wrappedValuexvg
- _$s7SwiftUI11StateObjectVMa
- _$s7SwiftUI11StateObjectVMn
- _$sSS11utf8CStrings15ContiguousArrayVys4Int8VGvg
- _$sSo24UISceneConnectionOptionsC19AppRestrictionsCoreE16preflightRequestSo012ALRPreflightH0CSgvg
- _os_variant_allows_internal_security_policies
- _swift_release_x1
CStrings:
+ "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
+ "LimitedModeShield"
+ "ManagementProviderStore"
+ "alr_preflightRequest"
- "Your Financial Provider"
```
