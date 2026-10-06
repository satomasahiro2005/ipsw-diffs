## SpringBoardUIServices

> `/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa19f4` | `0xa215c` | **`+0x768`** |
| `__AUTH_CONST.__objc_const` | `0x2d7c8` | `0x2d9f0` | **`+0x228`** |
| `__TEXT.__cstring` | `0xab02` | `0xac2f` | **`+0x12d`** |
| `__AUTH.__objc_data` | `0x5230` | `0x5320` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0xe5b4` | `0xe67c` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0xa1e0` | `0xa280` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c00` | `0x7c50` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3220` | `0x3260` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x4742` | `0x4771` | **`+0x2f`** |
| `__AUTH_CONST.__const` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2c00` | `0x2be8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x10a8` | `0x10c0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x978` | `0x990` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x994` | `0x988` | **`-0xc`** |
| `__DATA.__bss` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Other Changes

```diff

-4615.3.107.0.0
+4621.0.0.0.0

-  Functions: 4744
-  Symbols:   9348
-  CStrings:  1813
+  Functions: 4761
+  Symbols:   9381
+  CStrings:  1819
Symbols:
+ +[SBSUIAXUIServerReachabilityDisablingSceneExtension clientSettingsExtensions]
+ +[SBSUIAXUIServerReachabilityDisablingSceneExtension hostComponents]
+ +[SBSUIAXUIServerReachabilityDisablingSceneExtension isSupportedForScene:]
+ -[FBScene(SBSUIAXUIServerReachabilityDisabling) reachabilityDisablingFeaturePolicyHostComponent]
+ -[SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder _customizeWorkspaceRequestOptions:usingRequest:]
+ -[SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder _specification]
+ -[SBSUIAXUIServerReachabilityDisablingSceneSpecification defaultExtensions]
+ -[SBSUIAXUIServerReachabilityDisablingSceneSpecification uiSceneSessionRole]
+ -[SBUIBiometricResource _applyStrictTouchCoverageForAssertion:]
+ -[SBUIPresentationBinderIndirectAccessHostingSceneSpecification allowsHostedSoftwareKeyboard]
+ -[SBUISystemApertureCurtainEmbeddedSceneSpecification allowsHostedSoftwareKeyboard]
+ -[SBUISystemApertureEmbeddedSceneSpecification allowsHostedSoftwareKeyboard]
+ _OBJC_CLASS_$_FBScene
+ _OBJC_CLASS_$_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ _OBJC_CLASS_$_SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder
+ _OBJC_CLASS_$_SBSUIAXUIServerReachabilityDisablingSceneSpecification
+ _OBJC_METACLASS_$_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ _OBJC_METACLASS_$_SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder
+ _OBJC_METACLASS_$_SBSUIAXUIServerReachabilityDisablingSceneSpecification
+ _SBSUIWindowSceneSessionRoleAXUIServerReachabilityDisablingScene
+ __OBJC_$_CATEGORY_FBScene_$_SBSUIAXUIServerReachabilityDisabling
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_FBScene_$_SBSUIAXUIServerReachabilityDisabling
+ __OBJC_$_CLASS_METHODS_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ __OBJC_$_INSTANCE_METHODS_SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder
+ __OBJC_$_INSTANCE_METHODS_SBSUIAXUIServerReachabilityDisablingSceneSpecification
+ __OBJC_$_PROP_LIST_FBScene_$_SBSUIAXUIServerReachabilityDisabling
+ __OBJC_CLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ __OBJC_CLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder
+ __OBJC_CLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneSpecification
+ __OBJC_METACLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneExtension
+ __OBJC_METACLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneRequestBuilder
+ __OBJC_METACLASS_RO_$_SBSUIAXUIServerReachabilityDisablingSceneSpecification
+ ___76-[SBSUIAXUIServerReachabilityDisablingSceneSpecification uiSceneSessionRole]_block_invoke
+ ___block_descriptor_97_e8_32s40s48s56s64s72s80s_e73_v24?0"UIMutableApplicationSceneSettings"8"FBSSceneTransitionContext"16ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
- ___block_descriptor_89_e8_32s40s48s56s64s72s_e73_v24?0"UIMutableApplicationSceneSettings"8"FBSSceneTransitionContext"16ls32l8s40l8s48l8s56l8s64l8s72l8
CStrings:
+ "BKMatchTouchIDOperation"
+ "Incorrectly tried to retrieve reachabilityDisablingFeaturePolicyHostComponent"
+ "SBSUIAXUIServerReachabilityDisablingSceneSpecification.m"
+ "SBSUIWindowSceneSessionRoleAXUIServerReachabilityDisablingScene"
+ "TouchID operation required coverage set to: %@"
+ "Unexpectedly missing feature policy host component for scene that required it"
```
