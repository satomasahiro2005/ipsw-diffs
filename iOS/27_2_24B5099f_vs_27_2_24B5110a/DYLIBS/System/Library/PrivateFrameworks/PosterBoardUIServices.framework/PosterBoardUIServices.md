## PosterBoardUIServices

> `/System/Library/PrivateFrameworks/PosterBoardUIServices.framework/PosterBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x892d0` | `0x8a36c` | **`+0x109c`** |
| `__TEXT.__oslogstring` | `0x454f` | `0x4acf` | **`+0x580`** |
| `__AUTH_CONST.__objc_const` | `0x15080` | `0x15288` | **`+0x208`** |
| `__DATA.__data` | `0x2bf0` | `0x2c70` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x23f0` | `0x2460` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x6600` | `0x6668` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x1f8` | `0x248` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x3080` | `0x30c0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xde0` | `0xe18` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ac8` | `0x3b00` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1ce0` | `0x1d08` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x810` | `0x838` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3ba9` | `0x3bc9` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xa24` | `0xa40` | **`+0x1c`** |
| `__DATA.__objc_ivar` | `0x780` | `0x78c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-355.2.10.100.0
+355.2.12.101.0

-  Functions: 3555
-  Symbols:   5065
-  CStrings:  837
+  Functions: 3588
+  Symbols:   5083
+  CStrings:  855
Symbols:
+ +[PRUISModalEntryPointAcceptResponse responseWithUpdatedConfiguration:portalInfo:]
+ +[PRUISModalEntryPointAcceptResponse supportsBSXPCSecureCoding]
+ -[PRUISAmbientPosterViewController _updateHasSnapshot]
+ -[PRUISAmbientPosterViewController hasSnapshot]
+ -[PRUISAmbientPosterViewController sceneLayerManagerDidUpdateLayers:]
+ -[PRUISAmbientPosterViewController setHasSnapshot:]
+ -[PRUISModalEntryPointAcceptResponse .cxx_destruct]
+ -[PRUISModalEntryPointAcceptResponse copyWithZone:]
+ -[PRUISModalEntryPointAcceptResponse encodeWithBSXPCCoder:]
+ -[PRUISModalEntryPointAcceptResponse initWithBSXPCCoder:]
+ -[PRUISModalEntryPointAcceptResponse initWithUpdatedConfiguration:portalInfo:]
+ -[PRUISModalEntryPointAcceptResponse initWithUpdatedConfigurationPath:portalInfo:]
+ -[PRUISModalEntryPointAcceptResponse portalInfo]
+ -[PRUISModalEntryPointAcceptResponse updatedConfiguration]
+ -[PRUISModalRemoteViewController isScaledForEditing]
+ -[PRUISModalRemoteViewController setIsScaledForEditing:]
+ GCC_except_table104
+ GCC_except_table114
+ GCC_except_table122
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table69
+ _OBJC_CLASS_$_PRUISModalEntryPointAcceptResponse
+ _OBJC_IVAR_$_PRUISAmbientPosterViewController._hasSnapshot
+ _OBJC_IVAR_$_PRUISModalEntryPointAcceptResponse._portalInfo
+ _OBJC_IVAR_$_PRUISModalEntryPointAcceptResponse._updatedConfigurationPath
+ _OBJC_IVAR_$_PRUISModalRemoteViewController._isScaledForEditing
+ _OBJC_METACLASS_$_PRUISModalEntryPointAcceptResponse
+ __OBJC_$_CLASS_METHODS_PRUISModalEntryPointAcceptResponse
+ __OBJC_$_INSTANCE_METHODS_PRUISModalEntryPointAcceptResponse
+ __OBJC_$_INSTANCE_VARIABLES_PRUISModalEntryPointAcceptResponse
+ __OBJC_$_PROP_LIST_PRUISModalEntryPointAcceptResponse
+ __OBJC_CLASS_RO_$_PRUISModalEntryPointAcceptResponse
+ __OBJC_METACLASS_RO_$_PRUISModalEntryPointAcceptResponse
+ ___54-[PRUISAmbientPosterViewController _updateHasSnapshot]_block_invoke
+ ___block_descriptor_48_e8_32s40r_e24_v24?0"UIImageView"8Q16ls32l8r40l8
+ ___unnamed_44
- +[PRUISModalEntryPointGalleryAcceptResponse supportsBSXPCSecureCoding]
- -[PRUISModalEntryPointGalleryAcceptResponse .cxx_destruct]
- -[PRUISModalEntryPointGalleryAcceptResponse copyWithZone:]
- -[PRUISModalEntryPointGalleryAcceptResponse encodeWithBSXPCCoder:]
- -[PRUISModalEntryPointGalleryAcceptResponse initWithBSXPCCoder:]
- -[PRUISModalEntryPointGalleryAcceptResponse initWithPortalInfo:]
- -[PRUISModalEntryPointGalleryAcceptResponse portalInfo]
- GCC_except_table101
- GCC_except_table111
- GCC_except_table119
- GCC_except_table151
- GCC_except_table152
- GCC_except_table68
- _OBJC_IVAR_$_PRUISModalEntryPointGalleryAcceptResponse._portalInfo
- __OBJC_$_CLASS_METHODS_PRUISModalEntryPointGalleryAcceptResponse
- __OBJC_$_INSTANCE_METHODS_PRUISModalEntryPointGalleryAcceptResponse
- __OBJC_$_INSTANCE_VARIABLES_PRUISModalEntryPointGalleryAcceptResponse
- __OBJC_$_PROP_LIST_PRUISModalEntryPointGalleryAcceptResponse
- ___unnamed_43
CStrings:
+ "(no scene)"
+ "Effective presentation mode downgraded from Live: scene=%{public}@ contentState=%{public}@"
+ "PRUISModalEntryPointAcceptResponse: could not obtain poster path with sandbox extension: %@"
+ "Redundant presentationMode=Live set while scene is nil -- re-running update instead of treating this as a no-op."
+ "Scene reported ready but view controller's window is nil -- content ready with no host."
+ "_snapshotRequestDidFinishWithResult: cache was nil for request %{public}@ -- completion will not be called."
+ "buildPUISnapshotRequestForPriority: failed to load configured properties for path %{public}@: %{public}@"
+ "buildPUISnapshotRequestForPriority: snapshot definition identifier was nil/empty for path %{public}@"
+ "cacheSnapshotBundle:forRequest: cache unreachable for %{public}@: %{public}@"
+ "cacheSnapshotBundle:forRequest: failed to build underlying request for %{public}@: %{public}@"
+ "checkCacheIsReachable: cache unreachable: %{public}@"
+ "executeSnapshot: failed to build underlying snapshot request for %{public}@: %{public}@"
+ "latestSnapshotBundleForRequest: cache unreachable for %{public}@: %{public}@"
+ "latestSnapshotBundleForRequest: failed to build underlying request for %{public}@: %{public}@"
+ "latestSnapshotBundleForRequest: no cached snapshot found for %{public}@"
+ "presentationMode set to Live with no existing scene -- rebuilding."
+ "sceneDidDeactivate: presentationMode=%lu appearState=%ld isLive=%{public}@ isDisappeared=%{public}@"
+ "updatedConfigurationPath"
+ "\xa1"
+ "\xf0\xf0Q"
- "\x91"
- "\xf0\xf0A"
```
