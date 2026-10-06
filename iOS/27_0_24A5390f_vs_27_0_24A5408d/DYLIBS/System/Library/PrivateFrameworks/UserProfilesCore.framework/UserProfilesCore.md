## UserProfilesCore

> `/System/Library/PrivateFrameworks/UserProfilesCore.framework/UserProfilesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa110` | `0xb48c` | **`+0x137c`** |
| `__AUTH_CONST.__objc_const` | `0x2e50` | `0x3320` | **`+0x4d0`** |
| `__AUTH_CONST.__cfstring` | `0x960` | `0xb40` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x827` | `0x9d7` | **`+0x1b0`** |
| `__TEXT.__oslogstring` | `0x8a0` | `0x9e0` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xd4c` | `0xe34` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x910` | `0x998` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x418` | `0x498` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x500` | `0x550` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2f8` | `0x348` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb4` | `0xb8` | **`+0x4`** |

### Other Changes

```diff

-299.0.7.0.0
+299.0.11.0.0

-  Functions: 377
-  Symbols:   781
-  CStrings:  122
+  Functions: 419
+  Symbols:   819
+  CStrings:  144
Symbols:
+ -[UPSoftwareVersion isAfter:]
+ -[UPSoftwareVersion isBefore:]
+ -[UPSoftwareVersion isSameAs:]
+ -[UPSoftwareVersion isSameAsOrAfter:]
+ -[UPSoftwareVersion isSameAsOrBefore:]
+ -[UPSystemVersion .cxx_destruct]
+ -[UPSystemVersion buildVersion]
+ -[UPSystemVersion copyWithZone:]
+ -[UPSystemVersion debugDescription]
+ -[UPSystemVersion descriptionBuilderWithMultilinePrefix:]
+ -[UPSystemVersion descriptionWithMultilinePrefix:]
+ -[UPSystemVersion description]
+ -[UPSystemVersion hash]
+ -[UPSystemVersion initWithVersion:buildVersion:]
+ -[UPSystemVersion initWithVersionString:buildVersionString:]
+ -[UPSystemVersion isEqual:]
+ -[UPSystemVersion succinctDescriptionBuilder]
+ -[UPSystemVersion succinctDescription]
+ -[UPSystemVersion version]
+ _OBJC_CLASS_$_BSBuildVersion
+ _OBJC_CLASS_$_UPSystemVersion
+ _OBJC_IVAR_$_UPSystemVersion._buildVersion
+ _OBJC_IVAR_$_UPSystemVersion._version
+ _OBJC_METACLASS_$_UPSystemVersion
+ _OUTLINED_FUNCTION_10
+ _OUTLINED_FUNCTION_8
+ _OUTLINED_FUNCTION_9
+ __OBJC_$_INSTANCE_METHODS_UPSystemVersion
+ __OBJC_$_INSTANCE_VARIABLES_UPSystemVersion
+ __OBJC_$_PROP_LIST_UPSystemVersion
+ __OBJC_CLASS_PROTOCOLS_$_UPSystemVersion
+ __OBJC_CLASS_RO_$_UPSystemVersion
+ __OBJC_METACLASS_RO_$_UPSystemVersion
+ ___27-[UPSystemVersion isEqual:]_block_invoke
+ ___27-[UPSystemVersion isEqual:]_block_invoke_2
+ ___57-[UPSystemVersion descriptionBuilderWithMultilinePrefix:]_block_invoke
+ ___57-[UPSystemVersion descriptionBuilderWithMultilinePrefix:]_block_invoke_2
+ ___57-[UPSystemVersion descriptionBuilderWithMultilinePrefix:]_block_invoke_3
+ ___block_descriptor_40_e8_32s_e21_"BSBuildVersion"8?0ls32l8
+ ___block_descriptor_40_e8_32s_e24_"UPSoftwareVersion"8?0ls32l8
- -[UPPlatform buildVersion]
- _OBJC_IVAR_$_UPPlatform._buildVersion
CStrings:
+ "\""
+ "%@%lu"
+ "%lu%@%lu"
+ "@\"BSBuildVersion\"8@?0"
+ "@\"UPSoftwareVersion\"8@?0"
+ "BSBuildVersion"
+ "MobileGestalt returned no build version."
+ "MobileGestalt returned no product type."
+ "MobileGestalt returned no system version."
+ "UPSoftwareVersion"
+ "UPSystemVersion.m"
+ "Unable to create system version from strings. systemVersionString=%{public}@, buildVersionString=%{public}@"
+ "Unable to parse system version. versionString=%{public}@, buildVersionString=%{public}@"
+ "Value for '%@' was of unexpected class %@. Expected %@."
+ "Value for '%@' was unexpectedly nil. Expected %@."
+ "[_bs_assert_object isKindOfClass:BSBuildVersionClass]"
+ "[_bs_assert_object isKindOfClass:UPSoftwareVersionClass]"
+ "buildVersionString"
+ "majorBuildLetterString"
+ "majorBuildNumber"
+ "minorBuildLetterString"
+ "minorBuildNumber"
+ "version"
+ "versionString"
- "#"
- "%lu%@%lu%@%lu"
```
