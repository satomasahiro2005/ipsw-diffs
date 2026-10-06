## FamilyCircle

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/FamilyCircle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x5c8` | `0x22f8` | **`+0x1d30`** |
| `__AUTH.__objc_data` | `0x2588` | `0x8a8` | **`-0x1ce0`** |
| `__DATA_DIRTY.__data` | `0x168` | `0x14d8` | **`+0x1370`** |
| `__AUTH.__data` | `0x1b90` | `0x828` | **`-0x1368`** |
| `__TEXT.__text` | `0xca368` | `0xcaef4` | **`+0xb8c`** |
| `__DATA.__bss` | `0xbfc0` | `0xc1c0` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0xcaa0` | `0xcc98` | **`+0x1f8`** |
| `__AUTH_CONST.__const` | `0x6a78` | `0x6bc8` | **`+0x150`** |
| `__TEXT.__const` | `0x88c8` | `0x89c8` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x4f13` | `0x4fd3` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x4184` | `0x4214` | **`+0x90`** |
| `__DATA_DIRTY.__bss` | `0x160` | `0xe0` | **`-0x80`** |
| `__TEXT.__cstring` | `0x5fb4` | `0x6034` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1e7c` | `0x1ef8` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x161d` | `0x167d` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x4260` | `0x42a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3d28` | `0x3d68` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x28a8` | `0x28e0` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x5958` | `0x5980` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x282c` | `0x2850` | **`+0x24`** |
| `__TEXT.__swift5_assocty` | `0x5c8` | `0x5e0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2508` | `0x2520` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x13b0` | `0x13c0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x658` | `0x664` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x474` | `0x47c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2e4` | `0x2e8` | **`+0x4`** |

### Other Changes

```diff

-291.125.4.0.0
+291.125.7.0.0

-  Functions: 5566
-  Symbols:   4084
-  CStrings:  1322
+  Functions: 5593
+  Symbols:   4109
+  CStrings:  1334
Symbols:
+ +[FARestrictionsManagementSettings restrictionsManagementSettingsWithIsManaged:hasStrictPolicy:]
+ +[FARestrictionsManagementSettings supportsSecureCoding]
+ -[FARestrictionsManagementSettings .cxx_destruct]
+ -[FARestrictionsManagementSettings encodeWithCoder:]
+ -[FARestrictionsManagementSettings hasStrictPolicy]
+ -[FARestrictionsManagementSettings initWithCoder:]
+ -[FARestrictionsManagementSettings initWithIsManaged:hasStrictPolicy:]
+ -[FARestrictionsManagementSettings isManaged]
+ -[FASettingAccountRestrictionsRequest setRestrictionsWithAdditionalHeaders:managementSettings:completion:]
+ -[FASettingProtoAccountRestrictionsRequest setRestrictions:managementSettings:completion:]
+ _FAUniversalLinkActionShowFamilySettings
+ _OBJC_CLASS_$_FARestrictionsManagementSettings
+ _OBJC_IVAR_$_FARestrictionsManagementSettings._hasStrictPolicy
+ _OBJC_IVAR_$_FARestrictionsManagementSettings._isManaged
+ _OBJC_METACLASS_$_FARestrictionsManagementSettings
+ __OBJC_$_CLASS_METHODS_FARestrictionsManagementSettings
+ __OBJC_$_CLASS_PROP_LIST_FARestrictionsManagementSettings
+ __OBJC_$_INSTANCE_METHODS_FARestrictionsManagementSettings
+ __OBJC_$_INSTANCE_VARIABLES_FARestrictionsManagementSettings
+ __OBJC_$_PROP_LIST_FARestrictionsManagementSettings
+ __OBJC_CLASS_PROTOCOLS_$_FARestrictionsManagementSettings
+ __OBJC_CLASS_RO_$_FARestrictionsManagementSettings
+ __OBJC_METACLASS_RO_$_FARestrictionsManagementSettings
+ ___106-[FASettingAccountRestrictionsRequest setRestrictionsWithAdditionalHeaders:managementSettings:completion:]_block_invoke
+ ___106-[FASettingAccountRestrictionsRequest setRestrictionsWithAdditionalHeaders:managementSettings:completion:]_block_invoke_2
+ ___90-[FASettingProtoAccountRestrictionsRequest setRestrictions:managementSettings:completion:]_block_invoke
+ _associated conformance 12FamilyCircle29FAFamilyDeviceOperatingSystemOSHAASQ
+ _symbolic Say_____GSg 12FamilyCircle29FAFamilyDeviceOperatingSystemO
+ _symbolic _____ 12FamilyCircle29FAFamilyDeviceOperatingSystemO
- _FAUniversalLinkActionAddMember
- ___71-[FASettingProtoAccountRestrictionsRequest setRestrictions:completion:]_block_invoke
- ___87-[FASettingAccountRestrictionsRequest setRestrictionsWithAdditionalHeaders:completion:]_block_invoke
- ___87-[FASettingAccountRestrictionsRequest setRestrictionsWithAdditionalHeaders:completion:]_block_invoke_2
CStrings:
+ "HasStrictPolicy"
+ "IsManaged"
+ "SetUpFamilyRow"
+ "iOS"
+ "macOS"
+ "setRestrictionsWithAdditionalHeaders:completion: SPI is deprecated and not available. Please use setRestrictionsWithAdditionalHeaders:managementSettings:completion: instead"
+ "setRestrictionsWithCompletion SPI is deprecated and not available. Please use setRestrictionsWithAdditionalHeaders:managementSettings:completion: instead"
+ "setUpFamilyRow"
+ "showFamilySettings"
+ "tvOS"
+ "userInitiated"
+ "visionOS"
+ "watchOS"
+ "xrOS"
- "launchAddMember"
- "setRestrictionsWithCompletion SPI is deprecated and not available. Please use setRestrictionsWithAdditionalHeaders:completion: instead"
```
