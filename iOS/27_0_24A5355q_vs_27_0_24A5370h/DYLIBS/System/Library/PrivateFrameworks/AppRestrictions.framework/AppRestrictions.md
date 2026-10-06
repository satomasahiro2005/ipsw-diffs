## AppRestrictions

> `/System/Library/PrivateFrameworks/AppRestrictions.framework/AppRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xec50` | `0x10720` | **`+0x1ad0`** |
| `__TEXT.__oslogstring` | `0x142` | `0x262` | **`+0x120`** |
| `__TEXT.__cstring` | `0x3e8` | `0x4b7` | **`+0xcf`** |
| `__TEXT.__unwind_info` | `0x570` | `0x5d0` | **`+0x60`** |
| `__DATA.__data` | `0x4d8` | `0x530` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x108` | `0x158` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x6e8` | `0x738` | **`+0x50`** |
| `__TEXT.__const` | `0x908` | `0x958` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x608` | `0x650` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x1fc` | `0x240` | **`+0x44`** |
| `__DATA_CONST.__got` | `0x148` | `0x178` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x5cc` | `0x5fa` | **`+0x2e`** |
| `__DATA_CONST.__objc_selrefs` | `0x338` | `0x358` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x290` | `0x2a8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x540` | `0x550` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2c7` | `0x2d7` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x31c` | `0x328` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0x2b10` | `0x2b08` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x8d8` | `0x8d0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x64` | `0x68` | **`+0x4`** |

### Other Changes

```diff

-14.0.0.0.0
+19.0.0.0.0

-  Functions: 380
-  Symbols:   420
-  CStrings:  33
+  Functions: 407
+  Symbols:   431
+  CStrings:  44
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_UIMutableApplicationSceneSettings
+ _UIWindowSceneSessionRoleApplication
+ ___swift_allocate_boxed_opaque_existential_1
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _swift_bridgeObjectRelease_n
+ _swift_makeBoxUnique
+ _symbolic SDySSSaySDySSypGGG
+ _symbolic SDySSypG
+ _symbolic _____ 2os6LoggerV
+ _symbolic ______pSg 15AppRestrictions15PreflightSourceP
CStrings:
+ "%s: returning requiresPreflight FALSE as there's no activePreflightSource"
+ "%s: returning requiresPreflight FALSE as there's no component"
+ "AppManagedFeatures"
+ "PDUPreflightConfiguration"
+ "SceneHostedPreflight"
+ "UIApplicationSceneManifest"
+ "UISceneConfigurationName"
+ "UISceneConfigurations"
+ "[Preflighter: %{public}s] %{public}s requires preflight: %{bool}d"
+ "[Source: %{public}s] %{public}s requires preflight: %{bool}d"
+ "com.apple.PDUIApp"
+ "com.apple.preflight.PDUIApp"
- "ScenePreflighter"
```
