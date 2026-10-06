## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x279c78` | `0x27a4d0` | **`+0x858`** |
| `__TEXT.__cstring` | `0x14745` | `0x148a5` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x3e268` | `0x3e398` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0xc4c0` | `0xc5c0` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0xefbc` | `0xf03c` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x3bf0` | `0x3c40` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x9ce8` | `0x9d38` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1ea9a` | `0x1eaca` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x52a8` | `0x52d0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x9350` | `0x9370` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6d10` | `0x6d30` | **`+0x20`** |
| `__DATA.__bss` | `0x2f48` | `0x2f58` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1db8` | `0x1dc8` | **`+0x10`** |
| `__TEXT.__const` | `0x7314` | `0x7324` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1090` | `0x109c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2468` | `0x2470` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x750` | `0x758` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3e0` | `0x3e8` | **`+0x8`** |

### Other Changes

```diff

-355.0.5.0.0
+355.0.8.0.0

-  Functions: 10929
-  Symbols:   11118
-  CStrings:  4016
+  Functions: 10945
+  Symbols:   11146
+  CStrings:  4026
Symbols:
+ +[PBFPosterSnapshotThrottlePolicy new]
+ +[PBFPosterSnapshotThrottlePolicy policyForProvider:]
+ -[PBFPosterSnapshotManager _test_installProviderTrackers:enqueuePUIRequests:andRunKickoff:]
+ -[PBFPosterSnapshotThrottlePolicy captureTimeoutInterval]
+ -[PBFPosterSnapshotThrottlePolicy description]
+ -[PBFPosterSnapshotThrottlePolicy initWithMaximumConcurrentSnapshotters:captureTimeoutInterval:requestTimeoutInterval:]
+ -[PBFPosterSnapshotThrottlePolicy init]
+ -[PBFPosterSnapshotThrottlePolicy maximumConcurrentSnapshotters]
+ -[PBFPosterSnapshotThrottlePolicy requestTimeoutInterval]
+ _OBJC_CLASS_$_PBFPosterSnapshotThrottlePolicy
+ _OBJC_CLASS_$_PUIPosterSnapshotHostConfigurationDescriptor
+ _OBJC_IVAR_$_PBFPosterSnapshotThrottlePolicy._captureTimeoutInterval
+ _OBJC_IVAR_$_PBFPosterSnapshotThrottlePolicy._maximumConcurrentSnapshotters
+ _OBJC_IVAR_$_PBFPosterSnapshotThrottlePolicy._requestTimeoutInterval
+ _OBJC_METACLASS_$_PBFPosterSnapshotThrottlePolicy
+ _PBFPosterSnapshotDefaultRequestTimeoutInterval
+ _PRWidgetSnapshotRenderSessionTimeoutIsSufficient
+ __OBJC_$_CLASS_METHODS_PBFPosterSnapshotThrottlePolicy
+ __OBJC_$_INSTANCE_METHODS_PBFPosterSnapshotThrottlePolicy
+ __OBJC_$_INSTANCE_VARIABLES_PBFPosterSnapshotThrottlePolicy
+ __OBJC_$_PROP_LIST_PBFPosterSnapshotThrottlePolicy
+ __OBJC_CLASS_RO_$_PBFPosterSnapshotThrottlePolicy
+ __OBJC_METACLASS_RO_$_PBFPosterSnapshotThrottlePolicy
+ ___53+[PBFPosterSnapshotThrottlePolicy policyForProvider:]_block_invoke
+ ___91-[PBFPosterSnapshotManager _test_installProviderTrackers:enqueuePUIRequests:andRunKickoff:]_block_invoke
+ ___block_descriptor_105_e8_32s40s48s_e36_v16?0"<PRUISPosterSceneSettings>"8ls32l8s40l8s48l8
+ ___block_descriptor_40_e8_32s_e59_v32?0"NSString"8"PBFPosterSnapshotProviderTracker"16^B24ls32l8
+ _policyForProvider:.onceToken
+ _policyForProvider:.policiesByProvider
- ___block_descriptor_89_e8_32s40s_e36_v16?0"<PRUISPosterSceneSettings>"8ls32l8s40l8
CStrings:
+ "PRWidgetSnapshotRenderSessionTimeoutIsSufficient(captureTimeoutInterval)"
+ "captureTimeoutInterval"
+ "captureTimeoutInterval > 0"
+ "com.apple.WidgetFace.WidgetFaceExtension"
+ "maximumConcurrentSnapshotters"
+ "maximumConcurrentSnapshotters > 0"
+ "requestTimeoutInterval"
+ "requestTimeoutInterval > captureTimeoutInterval"
+ "throttling snapshots for provider %{public}@: %{public}@"
+ "v32@?0@\"NSString\"8@\"PBFPosterSnapshotProviderTracker\"16^B24"
```
