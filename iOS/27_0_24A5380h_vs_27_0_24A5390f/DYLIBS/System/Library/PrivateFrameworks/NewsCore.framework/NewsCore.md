## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/NewsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4128d0` | `0x4133d4` | **`+0xb04`** |
| `__AUTH_CONST.__objc_const` | `0x790f8` | `0x79498` | **`+0x3a0`** |
| `__AUTH_CONST.__cfstring` | `0x31a00` | `0x31be0` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x54974` | `0x54b04` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x34db0` | `0x34ef0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x18512` | `0x1860e` | **`+0xfc`** |
| `__AUTH.__objc_data` | `0x5b0` | `0x6a0` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a20` | `0x14a78` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x11408` | `0x11450` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xf028` | `0xf050` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x13e0` | `0x13f8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x2c68` | `0x2c80` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1ca0` | `0x1cb8` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x1590` | `0x15a8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4528` | `0x453c` | **`+0x14`** |
| `__DATA_DIRTY.__objc_ivar` | `0xfa0` | `0xfb0` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x2a88` | `0x2a90` | **`+0x8`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

-  Functions: 24858
-  Symbols:   37548
-  CStrings:  10480
+  Functions: 24884
+  Symbols:   37607
+  CStrings:  10497
Symbols:
+ -[FCNewsTabiConfiguration groupFormationConfiguration]
+ -[FCNewsTabiConfiguration groupFormationEndpoint]
+ -[FCNewsTabiConfiguration setGroupFormationEndpoint:]
+ -[FCNewsTabiFeedPersonalizationConfiguration nonMtBundleOutputConfiguration]
+ -[FCNewsTabiFeedPersonalizationConfiguration nonMtNonBundleOutputConfiguration]
+ -[FCNewsTabiFeedPersonalizationConfiguration setNonMtBundleOutputConfiguration:]
+ -[FCNewsTabiFeedPersonalizationConfiguration setNonMtNonBundleOutputConfiguration:]
+ -[FCNewsTabiGroupFormationCapabilities bestOfClustering]
+ -[FCNewsTabiGroupFormationCapabilities description]
+ -[FCNewsTabiGroupFormationCapabilities initWithDictionary:]
+ -[FCNewsTabiGroupFormationCapabilities init]
+ -[FCNewsTabiGroupFormationCapabilities multiGroupClustering]
+ -[FCNewsTabiGroupFormationConfiguration .cxx_destruct]
+ -[FCNewsTabiGroupFormationConfiguration bestOfInventoryPrefixLimit]
+ -[FCNewsTabiGroupFormationConfiguration capabilities]
+ -[FCNewsTabiGroupFormationConfiguration description]
+ -[FCNewsTabiGroupFormationConfiguration initWithDictionary:]
+ -[FCNewsTabiGroupFormationConfiguration init]
+ -[FCNewsTabiGroupFormationEndpoint .cxx_destruct]
+ -[FCNewsTabiGroupFormationEndpoint configuration]
+ -[FCNewsTabiGroupFormationEndpoint description]
+ -[FCNewsTabiGroupFormationEndpoint initWithDictionary:]
+ -[FCNewsTabiGroupFormationEndpoint init]
+ -[FCNewsTabiGroupFormationEndpoint packageAssetID]
+ _OBJC_CLASS_$_FCNewsTabiGroupFormationCapabilities
+ _OBJC_CLASS_$_FCNewsTabiGroupFormationConfiguration
+ _OBJC_CLASS_$_FCNewsTabiGroupFormationEndpoint
+ _OBJC_IVAR_$_FCNewsTabiConfiguration._groupFormationEndpoint
+ _OBJC_IVAR_$_FCNewsTabiGroupFormationCapabilities._bestOfClustering
+ _OBJC_IVAR_$_FCNewsTabiGroupFormationCapabilities._multiGroupClustering
+ _OBJC_IVAR_$_FCNewsTabiGroupFormationEndpoint._configuration
+ _OBJC_IVAR_$_FCNewsTabiGroupFormationEndpoint._packageAssetID
+ _OBJC_METACLASS_$_FCNewsTabiGroupFormationCapabilities
+ _OBJC_METACLASS_$_FCNewsTabiGroupFormationConfiguration
+ _OBJC_METACLASS_$_FCNewsTabiGroupFormationEndpoint
+ __OBJC_$_INSTANCE_METHODS_FCNewsTabiGroupFormationCapabilities
+ __OBJC_$_INSTANCE_METHODS_FCNewsTabiGroupFormationConfiguration
+ __OBJC_$_INSTANCE_METHODS_FCNewsTabiGroupFormationEndpoint
+ __OBJC_$_INSTANCE_VARIABLES_FCNewsTabiGroupFormationCapabilities
+ __OBJC_$_INSTANCE_VARIABLES_FCNewsTabiGroupFormationConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_FCNewsTabiGroupFormationEndpoint
+ __OBJC_$_PROP_LIST_FCNewsTabiGroupFormationCapabilities
+ __OBJC_$_PROP_LIST_FCNewsTabiGroupFormationConfiguration
+ __OBJC_$_PROP_LIST_FCNewsTabiGroupFormationEndpoint
+ __OBJC_CLASS_RO_$_FCNewsTabiGroupFormationCapabilities
+ __OBJC_CLASS_RO_$_FCNewsTabiGroupFormationConfiguration
+ __OBJC_CLASS_RO_$_FCNewsTabiGroupFormationEndpoint
+ __OBJC_METACLASS_RO_$_FCNewsTabiGroupFormationCapabilities
+ __OBJC_METACLASS_RO_$_FCNewsTabiGroupFormationConfiguration
+ __OBJC_METACLASS_RO_$_FCNewsTabiGroupFormationEndpoint
+ ___55-[FCNewsTabiGroupFormationEndpoint initWithDictionary:]_block_invoke
+ _kFCNewsTabiFeedPersonalizationConfigurationNonMTBundleOutputConfigurationKey
+ _kFCNewsTabiFeedPersonalizationConfigurationNonMTNonBundleOutputConfigurationKey
+ _kFCNewsTabiGroupFormationCapabilitiesBestOfClusteringKey
+ _kFCNewsTabiGroupFormationCapabilitiesMultiGroupClusteringKey
+ _kFCNewsTabiGroupFormationConfigurationBestOfInventoryPrefixLimitKey
+ _kFCNewsTabiGroupFormationConfigurationCapabilitiesKey
+ _kFCNewsTabiGroupFormationConfigurationKey
+ _kFCNewsTabiGroupFormationEndpointPackageAssetIDKey
CStrings:
+ "\n\tbestOfClustering: %@"
+ "\n\tbestOfInventoryPrefixLimit: %ld"
+ "\n\tcapabilities: %@"
+ "\n\tgroupFormationEndpoint: %@;"
+ "\n\tmultiGroupClustering: %@"
+ "\n\tnonMtBundleOutputConfiguration: %@"
+ "\n\tnonMtNonBundleOutputConfiguration: %@"
+ "Failed to initialize FCNewsTabiGroupFormationConfiguration due to failure to decode configuration from configuration %{public}@"
+ "Failed to initialize FCNewsTabiGroupFormationEndpoint due to failure to decode packageAssetID from configuration %{public}@"
+ "bestOfClustering"
+ "bestOfInventoryPrefixLimit"
+ "capabilities"
+ "group-formation"
+ "groupFormationConfiguration"
+ "multiGroupClustering"
+ "nonMtBundleOutputConfiguration"
+ "nonMtNonBundleOutputConfiguration"
```
