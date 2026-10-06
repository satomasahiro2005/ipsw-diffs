## AppSSO

> `/System/Library/PrivateFrameworks/AppSSO.framework/AppSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2bca8` | `0x2bf94` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x4c95` | `0x4ce8` | **`+0x53`** |
| `__TEXT.__gcc_except_tab` | `0x195c` | `0x19a4` | **`+0x48`** |
| `__TEXT.__cstring` | `0x3806` | `0x383c` | **`+0x36`** |
| `__AUTH_CONST.__cfstring` | `0x1320` | `0x1340` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Other Changes

```diff

-643.0.47.0.0
+643.40.23.0.0

-  Functions: 1065
+  Functions: 1068

-  CStrings:  733
+  CStrings:  735
Functions:
~ _AppSSOCoreLibrary : 256 -> 252
~ _AppSSOCoreLibrary : 80 -> 256
~ _AppSSOCoreLibrary : 252 -> 80
~ _AppSSOCoreLibrary : 92 -> 252
+ _AppSSOCoreLibrary
~ -[SODDMConfigurationHost applyConfiguration:replaceKey:error:] : 1140 -> 1724
~ ___getSOErrorHelperClass_block_invoke : 324 -> 88
+ ___getSOFullProfileClass_block_invoke
+ -[SODDMConfigurationHost loadDDMConfigurationsWithError:].cold.1
+ ___getSOAuthorizationResultCoreClass_block_invoke.cold.1
- ___getSOFullProfileClass_block_invoke.cold.1
CStrings:
+ "Only a single Platform SSO configuration is supported"
+ "Rejecting configuration: more than one Platform SSO configuration is not supported"
```
