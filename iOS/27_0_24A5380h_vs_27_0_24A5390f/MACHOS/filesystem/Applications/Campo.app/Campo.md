## Campo

> `/Applications/Campo.app/Campo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdddc` | `0xed80` | **`+0xfa4`** |
| `__TEXT.__eh_frame` | `0xa00` | `0xb70` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x640` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0xe90` | **`+0x50`** |
| `__TEXT.__const` | `0x644` | `0x684` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x268` | `0x2a0` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x60` | `0x94` | **`+0x34`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x750` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x462` | `0x43e` | **`-0x24`** |
| `__TEXT.__cstring` | `0x3bd` | `0x3dd` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x17dc` | `0x17bc` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0xda2` | `0xd82` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x720` | `0x700` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x208` | `0x1f0` | **`-0x18`** |
| `__DATA.__data` | `0x8b8` | `0x8a8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x230` | `0x220` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x48` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x520` | `0x518` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x38` | `0x40` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-73.0.5.102.0
+73.0.12.0.0

+  - /System/Library/PrivateFrameworks/SnippetUI.framework/SnippetUI

-  Functions: 498
-  Symbols:   397
-  CStrings:  316
+  Functions: 528
+  Symbols:   398
+  CStrings:  315
Symbols:
+ _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5Scale11colorSchemeSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVAsQ7SwiftUI05ColorQ0OtYaF
+ _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5Scale11colorSchemeSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVAsQ7SwiftUI05ColorQ0OtYaFTu
+ _$s15CampoUIInternal29CarPlayConversationDataSourceC17isSiriUnavailableSbyF
+ _$s15CampoUIInternal29CarPlayConversationDataSourceC22isSiriUpdateInProgressSbyF
+ _$s9SnippetUI22VisualResponseProviderC14preloadPluginsyyFZ
+ _$s9SnippetUI22VisualResponseProviderCMa
+ _$sSS15CampoUIInternalE0A0V38siriUnavailableCarPlayPlaceholderTitleSSvgZ
+ _$sSS15CampoUIInternalE0A0V43siriUpdateInProgressCarPlayPlaceholderTitleSSvgZ
+ _$sSS15CampoUIInternalE0A0V46siriUpdateInProgressCarPlayPlaceholderSubtitleSSvgZ
+ _$sSa10FoundationE36_unconditionallyBridgeFromObjectiveCySayxGSo7NSArrayCSgFZ
+ _objc_release_x27
+ _objc_retain_x27
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
- _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5ScaleSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVArPtYaF
- _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5ScaleSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVArPtYaFTu
- _$s15CampoUIInternal18CarPlayImageLoaderC11colorScheme7SwiftUI05ColorH0Ovs
- _$s21AssistantIslandClient0abC14VoiceSceneViewV7SwiftUI0F0AAMc
- _$s21AssistantIslandClient0abC14VoiceSceneViewVMa
- _$s21AssistantIslandClient0abC14VoiceSceneViewVMn
- _$s21AssistantIslandClient0abC14VoiceSceneViewVyACSo8FBSSceneCcfC
- _$s21AssistantIslandClient0abC15VoiceSceneGroupV7contentACyxGxSo8FBSSceneCc_tcfC
- _$s21AssistantIslandClient0abC15VoiceSceneGroupVMn
- _CPImageByScalingImageToSize
- _OBJC_CLASS_$_NSBundle
- _objc_release_x26
- _objc_release_x28
- _objc_retain_x26
CStrings:
+ "emptyViewTitleVariants"
+ "initWithLightContentImage:darkContentImage:"
+ "setEmptyViewSubtitleVariants:"
+ "square.and.pencil"
+ "systemImageNamed:"
- "@\"UIImage\"16@?0@\"UIImage\"8"
- "bundleForClass:"
- "imageNamed:inBundle:withConfiguration:"
- "initWithImage:treatmentBlock:"
- "maximumImageSize"
- "userInterfaceStyle"
```
