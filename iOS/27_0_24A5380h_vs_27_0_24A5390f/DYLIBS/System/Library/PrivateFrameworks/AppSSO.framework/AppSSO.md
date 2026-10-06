## AppSSO

> `/System/Library/PrivateFrameworks/AppSSO.framework/AppSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2baac` | `0x2bca8` | **`+0x1fc`** |
| `__TEXT.__oslogstring` | `0x4bb8` | `0x4c95` | **`+0xdd`** |
| `__TEXT.__cstring` | `0x37d9` | `0x3806` | **`+0x2d`** |
| `__TEXT.__objc_methlist` | `0x1c2c` | `0x1c54` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x12f8` | `0x1318` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe28` | `0xe40` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1958` | `0x195c` | **`+0x4`** |

### Other Changes

```diff

-643.0.21.0.0
+643.0.33.0.0

-  Functions: 1067
-  Symbols:   1487
-  CStrings:  731
+  Functions: 1065
+  Symbols:   1490
+  CStrings:  733
Symbols:
+ -[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]
+ -[SOConfigurationHost _profileMatchesTeamIdentifier:requiredTeamIdentifier:]
+ -[SOConfigurationHost hasAnyMDMProfileForExtension:teamIdentifier:]
+ -[SOConfigurationHost isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]
+ GCC_except_table25
+ GCC_except_table37
+ GCC_except_table38
+ GCC_except_table39
+ GCC_except_table43
+ GCC_except_table51
+ GCC_except_table56
+ ___108-[SOConfigurationHost isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]_block_invoke
+ ___109-[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]_block_invoke
+ ___block_descriptor_65_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- -[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:runningAsAgent:completion:]
- GCC_except_table23
- GCC_except_table24
- GCC_except_table33
- GCC_except_table34
- GCC_except_table46
- _OUTLINED_FUNCTION_13
- ___93-[SOConfigurationHost isConfigurationActiveForExtensionIdentifier:runningAsAgent:completion:]_block_invoke
- ___94-[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:runningAsAgent:completion:]_block_invoke
- ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- _objc_retain_x25
CStrings:
+ "%s extensionIdentifier: %{public}@, teamIdentifier: %{public}@ on %@"
+ "-[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]"
+ "-[SOConfigurationHost hasAnyMDMProfileForExtension:teamIdentifier:]"
+ "-[SOConfigurationHost isConfigurationActiveForExtensionIdentifier:teamIdentifier:runningAsAgent:completion:]"
+ "ignoring profile team identifier mismatch because extension signature validation is disabled"
+ "profile team identifier mismatch for extension: %{public}@, profile=%{public}@, required=%{public}@"
- "%s extensionIdentifier: %{public}@ on %@"
- "-[SOConfigurationHost _isConfigurationActiveForExtensionIdentifier:runningAsAgent:completion:]"
- "-[SOConfigurationHost hasAnyMDMProfileForExtension:]"
- "-[SOConfigurationHost isConfigurationActiveForExtensionIdentifier:runningAsAgent:completion:]"
```
