## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bca1dc` | `0x1bcb194` | **`+0xfb8`** |
| `__TEXT.__cstring` | `0x10192d` | `0x101b1d` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0x54951` | `0x54b26` | **`+0x1d5`** |
| `__TEXT.__const` | `0x4c598` | `0x4c6a8` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x560a8` | `0x561a0` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0x5bc60` | `0x5bd58` | **`+0xf8`** |
| `__AUTH_CONST.__cfstring` | `0xb3680` | `0xb3720` | **`+0xa0`** |
| `__DATA.__bss` | `0x3dd38` | `0x3ddd8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x1d4e0` | `0x1d574` | **`+0x94`** |
| `__DATA.__data` | `0x328e0` | `0x32970` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x2791c8` | `0x279228` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x16e98` | `0x16ef4` | **`+0x5c`** |
| `__DATA_DIRTY.__data` | `0xb9aa` | `0xb97a` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x175de` | `0x1760e` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x71f60` | `0x71f90` | **`+0x30`** |
| `__AUTH.__data` | `0xa500` | `0xa520` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x15d30` | `0x15d50` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x18cb4` | `0x18cca` | **`+0x16`** |
| `__TEXT.__swift5_builtin` | `0x1324` | `0x1338` | **`+0x14`** |
| `__DATA_DIRTY.__uikit_ip` | `0x11a0` | `0x11b0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x19fa30` | `0x19fa40` | **`+0x10`** |
| `__DATA.__uikit_ip` | `0x998` | `0x990` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xb330` | `0xb338` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x95c30` | `0x95c28` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x1bb4` | `0x1bbc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x11d90` | `0x11d8c` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x24f8` | `0x24fc` | **`+0x4`** |

### Other Changes

```diff

-9127.0.84.1.102
+9127.0.84.1.902

-  Functions: 181252
-  Symbols:   228726
-  CStrings:  33748
+  Functions: 181271
+  Symbols:   228738
+  CStrings:  33767
Symbols:
+ -[TIAutocorrectionList(DebugDescription) nonsensitiveDescription]
+ _OBJC_METACLASS_$__TtC5UIKitP33_C5DEBA7E6AD43E2A3FA4230D58A6D9B324UIKitMorphNoopUpdateLink
+ _PredictionViewControllerUILog
+ __DATA__TtC5UIKitP33_C5DEBA7E6AD43E2A3FA4230D58A6D9B324UIKitMorphNoopUpdateLink
+ __INSTANCE_METHODS__TtC5UIKitP33_C5DEBA7E6AD43E2A3FA4230D58A6D9B324UIKitMorphNoopUpdateLink
+ __IVARS__TtC5UIKitP33_C5DEBA7E6AD43E2A3FA4230D58A6D9B324UIKitMorphNoopUpdateLink
+ __METACLASS_DATA__TtC5UIKitP33_C5DEBA7E6AD43E2A3FA4230D58A6D9B324UIKitMorphNoopUpdateLink
+ __OBJC_$_INSTANCE_METHODS_TIAutocorrectionList(UIKitSupplementalItemExtras|UIKeyboardAdditions|UIKBExtras|DebugDescription)
+ __UIInternalPreference_DisablePassthroughWindow_block_invoke_5.__s_category
+ __UIKeyboardGetDeviceIdiomFromInputUIScene.__reentranceGuard
+ ___99-[UIWindowScene _updateSceneTraitsAndPushTraitsToScreen:callParentWillTransitionToTraitCollection:]_block_invoke
+ ___KeyboardAutocorrectionControllerUI_block_invoke
+ ___PredictionViewControllerUILog_block_invoke
+ ___swift_memcpy12_4
+ __updateSceneTraitsAndPushTraitsToScreen:callParentWillTransitionToTraitCollection:.once
+ _symbolic _____ 5UIKit0A19MorphNoopUpdateLink33_C5DEBA7E6AD43E2A3FA4230D58A6D9B3LLC
+ _symbolic _____ So16CAFrameRateRangeV
+ _type_layout_string So16CAFrameRateRangeV
- -[_UIDoubleTapInteraction consumesFirstTap]
- -[_UIDoubleTapInteraction setConsumesFirstTap:]
- _OBJC_IVAR_$__UIDoubleTapInteraction._consumesFirstTap
- __OBJC_$_INSTANCE_METHODS_TIAutocorrectionList(UIKitSupplementalItemExtras|UIKeyboardAdditions|UIKBExtras)
- __UIInternalPreference_ContextMenuRespectsIntelligentAssistantPreferredVisibilityHidden
- ___38-[_UIDoubleTapInteraction _captureTap]_block_invoke_2
CStrings:
+ " corrections=%lu"
+ " emojiList=%lu"
+ " predictions=%lu"
+ "%s, %{public}@"
+ "-[UIKeyboardAutocorrectionController setAutocorrectionList:]"
+ "-[UIPredictionViewController _updateAutocorrectionList:candidateGenerationContext:]"
+ ". Falling back to no-op update link."
+ "; has windowScene: "
+ "<%@: %p isRedacted=YES>"
+ "Autocorrection list is redacted. Presenting securely hosted input candidate view."
+ "ContextMenuLooksUpIntelligentAssistantAvailabilityFromScene"
+ "Failed to create geometryTrackingUpdateLink for "
+ "Ignoring scene traits update for invalidated scene %{public}@ (%{public}@)"
+ "KeyboardAutocorrectionControllerUI"
+ "PredictionViewControllerUI"
+ "Presenting current text suggestions."
+ "UIPredictionViewController autocorrection list update has been throttled."
+ "UIPredictionViewController setting autocorrection list on TUIPredictionView, %{public}@"
+ "_setKeyWindowSceneInputViews: containedInputWindowController is nil, setting input views may fail"
```
