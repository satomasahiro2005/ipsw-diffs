## imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11790` | `0x10fe4` | **`-0x7ac`** |
| `__TEXT.__oslogstring` | `0x90e` | `0x89e` | **`-0x70`** |
| `__TEXT.__auth_stubs` | `0xf40` | `0xef0` | **`-0x50`** |
| `__TEXT.__cstring` | `0x3dc` | `0x38c` | **`-0x50`** |
| `__TEXT.__eh_frame` | `0xe88` | `0xe38` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x499` | `0x469` | **`-0x30`** |
| `__DATA_CONST.__auth_got` | `0x7a8` | `0x780` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x4c8` | `0x4a0` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x260` | **`-0x20`** |
| `__DATA.__data` | `0xac0` | `0xab0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x520` | `0x510` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x140` | `0x138` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x208` | `0x200` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xac` | `0xa4` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-194.1.0.0.0
+198.1.0.0.0

-  Functions: 285
-  Symbols:   370
-  CStrings:  143
+  Functions: 282
+  Symbols:   364
+  CStrings:  140
Symbols:
+ _$s14SuggestedImage30PosterBoardDescriptorRefresherO7refreshyyYaKFZ
+ _$s14SuggestedImage30PosterBoardDescriptorRefresherO7refreshyyYaKFZTu
- _$s10Foundation4DateV11descriptionSSvg
- _$s14SuggestedImage25GenerationStaggerScheduleO08isWithinC6Window3now8defaultsSb10Foundation4DateV_So14NSUserDefaultsCtFZ
- _$s14SuggestedImage25GenerationStaggerScheduleO12WindowStatusV7opensAt10Foundation4DateVvg
- _$s14SuggestedImage25GenerationStaggerScheduleO12WindowStatusVMa
- _$s14SuggestedImage25GenerationStaggerScheduleO6status3now8defaultsAC12WindowStatusV10Foundation4DateV_So14NSUserDefaultsCtFZ
- _$sSo14NSUserDefaultsC14SuggestedImageE06daemonB0ABvgZ
- _OBJC_CLASS_$_NSUserDefaults
- _OBJC_CLASS_$__PosterBoardServices
CStrings:
- "Outside this device's generation window; deferring personalization production until next slot at %{public}s."
- "com.apple.Posters.ImagePlaygroundPosterApp.ImagePlaygroundPoster"
- "refreshPosterDescriptorsForExtension:completion:"
```
