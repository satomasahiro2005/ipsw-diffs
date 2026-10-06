## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb09e38` | `0xb0a100` | **`+0x2c8`** |
| `__AUTH_CONST.__objc_const` | `0x2879f0` | `0x287bc8` | **`+0x1d8`** |
| `__TEXT.__objc_methlist` | `0xbdb48` | `0xbdc30` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e8b0` | `0x4e920` | **`+0x70`** |
| `__DATA.__data` | `0x20ec0` | `0x20f20` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x64eda` | `0x64e7b` | **`-0x5f`** |
| `__TEXT.__unwind_info` | `0x2e530` | `0x2e548` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x2ad0` | `0x2ad8` | **`+0x8`** |

### Other Changes

```diff

-4636.112.0.0.0
+4636.115.0.0.0

-  Functions: 73497
-  Symbols:   119271
-  CStrings:  23492
+  Functions: 73508
+  Symbols:   119288
+  CStrings:  23491
Symbols:
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider _hostWouldPresentLiveContentIfReady]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider _makePreflightViewController]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider _updateActivation]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider noteDisplayModeChange:]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider noteLiveContentDisableReasonsChanged]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider sceneHandle:didCreateScene:]
+ -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider sceneHandle:didDestroyScene:]
+ -[SBDeviceApplicationSceneOverlayViewProvider noteLiveContentDisableReasonsChanged]
+ -[SBDeviceApplicationSceneViewController overlayViewProviderHostDisplayMode:]
+ -[SBDeviceApplicationSceneViewController overlayViewProviderHostLiveContentDisableReasons:]
+ -[SBDeviceApplicationSceneViewController overlayViewProviderHostPresentationPriority:]
+ -[SBDeviceApplicationSceneViewController sceneViewDidChangeLiveContentDisableReasons:]
+ -[SBRecordingIndicatorManager _systemApertureHighLevelGainMapDefeatingLayer]
+ -[SBRecordingIndicatorSystemApertureElement highLevelContainerRenderingConfigurationDidChange:]
+ -[SBRecordingIndicatorViewController highLevelGainMapDefeatingLayer]
+ GCC_except_table110
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SBSystemApertureHighLevelContainerRenderingObserving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SBSystemApertureHighLevelContainerRenderingObserving
+ __OBJC_$_PROTOCOL_REFS_SBSystemApertureHighLevelContainerRenderingObserving
+ __OBJC_LABEL_PROTOCOL_$_SBSystemApertureHighLevelContainerRenderingObserving
+ __OBJC_PROTOCOL_$_SBSystemApertureHighLevelContainerRenderingObserving
- -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider sceneDidInvalidate:]
- -[SBDeviceApplicationAppRestrictionSceneOverlayViewProvider sceneManager:didAddScene:]
- _OUTLINED_FUNCTION_36
- _OUTLINED_FUNCTION_37
CStrings:
+ "[%{public}@] didCreateScene"
+ "[%{public}@] didDestroyScene"
+ "[%{public}@] init without scene; waiting for scene creation"
- "[%{public}@] didAddScene"
- "[%{public}@] init without scene; waiting for scene manager"
- "[%{public}@] requiresPreflight = NO; waiting for preflight callback"
- "[%{public}@] requiresPreflight = YES; attempting activation"
```
