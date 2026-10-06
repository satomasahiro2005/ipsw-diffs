## AppManagedFeatures

> `/System/Library/Frameworks/AppManagedFeatures.framework/AppManagedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x7180` | `0x6900` | **`-0x880`** |
| `__DATA_DIRTY.__bss` | `0x300` | `0xb80` | **`+0x880`** |
| `__DATA_DIRTY.__data` | `0xb0` | `0x5c0` | **`+0x510`** |
| `__DATA.__data` | `0xd68` | `0xab8` | **`-0x2b0`** |
| `__AUTH.__data` | `0x6f8` | `0x4a8` | **`-0x250`** |
| `__TEXT.__text` | `0x6dd10` | `0x6ddf8` | **`+0xe8`** |
| `__TEXT.__swift5_reflstr` | `0xdcc` | `0xe9c` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x2443` | `0x2503` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x3130` | `0x31d8` | **`+0xa8`** |
| `__TEXT.__const` | `0x6c40` | `0x6ce0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xf44` | `0xf90` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x112c` | `0x1148` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x16d9` | `0x16cb` | **`-0xe`** |
| `__TEXT.__swift5_types` | `0x120` | `0x124` | **`+0x4`** |

### Other Changes

```diff

-46.0.1.0.0
+46.0.5.0.0

-  Functions: 2049
-  Symbols:   636
-  CStrings:  254
+  Functions: 2052
+  Symbols:   637
+  CStrings:  257
Symbols:
+ __INSTANCE_METHODS__TtC18AppManagedFeatures41_AppManagedFeaturesExtensionConfiguration
+ __IVARS__TtC18AppManagedFeatures41_AppManagedFeaturesExtensionConfiguration
+ __PROTOCOLS__TtC18AppManagedFeatures41_AppManagedFeaturesExtensionConfiguration
+ ___unnamed_18
+ _get_witness_table 18AppManagedFeatures0abC9ExtensionRzlAA01_abcD13ConfigurationCyxGAA0abcdE0HPyHC
+ _symbolic $s18AppManagedFeatures0abC22ExtensionConfigurationP
+ _symbolic $s18AppManagedFeatures0abC9ExtensionP
+ _symbolic _____ 18AppManagedFeatures01_abC22ExtensionConfigurationC
+ _symbolic _____ 18AppManagedFeatures0abC9ConstantsO010DiagnosticD0O
+ _symbolic _____yxG 18AppManagedFeatures01_abC22ExtensionConfigurationC
- __INSTANCE_METHODS__TtC18AppManagedFeatures33_ActivationExtensionConfiguration
- __IVARS__TtC18AppManagedFeatures33_ActivationExtensionConfiguration
- __PROTOCOLS__TtC18AppManagedFeatures33_ActivationExtensionConfiguration
- ___unnamed_16
- _get_witness_table 18AppManagedFeatures19ActivationExtensionRzlAA01_dE13ConfigurationCyxGAA0deF0HPyHC
- _symbolic $s18AppManagedFeatures19ActivationExtensionP
- _symbolic $s18AppManagedFeatures32ActivationExtensionConfigurationP
- _symbolic _____ 18AppManagedFeatures33_ActivationExtensionConfigurationC
- _symbolic _____yxG 18AppManagedFeatures33_ActivationExtensionConfigurationC
CStrings:
+ "AppManagedFeatures._AppManagedFeaturesExtensionConfiguration"
+ "Find My partner financing enrollment failed during activation."
+ "appManagedFeaturesEnrollmentFailed"
+ "com.apple.appmanagedfeatures.limitedmodecheckinhandler.complete"
- "AppManagedFeatures._ActivationExtensionConfiguration"
```
