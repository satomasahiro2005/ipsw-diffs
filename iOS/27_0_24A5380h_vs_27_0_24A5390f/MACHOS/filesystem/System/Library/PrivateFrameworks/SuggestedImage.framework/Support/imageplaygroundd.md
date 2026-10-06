## imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1005c` | `0x11790` | **`+0x1734`** |
| `__TEXT.__oslogstring` | `0x72f` | `0x90e` | **`+0x1df`** |
| `__TEXT.__eh_frame` | `0xd48` | `0xe88` | **`+0x140`** |
| `__TEXT.__auth_stubs` | `0xe60` | `0xf40` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x31b` | `0x3dc` | **`+0xc1`** |
| `__DATA_CONST.__auth_got` | `0x738` | `0x7a8` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x439` | `0x499` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x240` | `0x280` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x208` | **`+0x38`** |
| `__DATA.__data` | `0xa90` | `0xac0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x520` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4a0` | `0x4c8` | **`+0x28`** |
| `__TEXT.__const` | `0x8c8` | `0x8e0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa4` | `0xac` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-193.1.0.0.0
+194.1.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 277
-  Symbols:   349
-  CStrings:  131
+  Functions: 285
+  Symbols:   370
+  CStrings:  143
Symbols:
+ _$s10Foundation4DateV11descriptionSSvg
+ _$s14SuggestedImage25GenerationStaggerScheduleO08isWithinC6Window3now8defaultsSb10Foundation4DateV_So14NSUserDefaultsCtFZ
+ _$s14SuggestedImage25GenerationStaggerScheduleO12WindowStatusV7opensAt10Foundation4DateVvg
+ _$s14SuggestedImage25GenerationStaggerScheduleO12WindowStatusVMa
+ _$s14SuggestedImage25GenerationStaggerScheduleO6status3now8defaultsAC12WindowStatusV10Foundation4DateV_So14NSUserDefaultsCtFZ
+ _$s14SuggestedImage27DefaultGenerationControllerV06handleD8Requests3for13configuration15progressHandleryAA7UseCaseOSg_AC07RequestD13ConfigurationVyAA0D13ProgressEventOYbcSgtYaKF
+ _$s14SuggestedImage27DefaultGenerationControllerV06handleD8Requests3for13configuration15progressHandleryAA7UseCaseOSg_AC07RequestD13ConfigurationVyAA0D13ProgressEventOYbcSgtYaKFTu
+ _$s14SuggestedImage27DefaultGenerationControllerV07RequestD13ConfigurationV7triggerAeC7TriggerO_tcfC
+ _$s14SuggestedImage27DefaultGenerationControllerV07RequestD13ConfigurationVMa
+ _$s14SuggestedImage27DefaultGenerationControllerV7TriggerO18backgroundScheduleyA2EmFWC
+ _$s14SuggestedImage27DefaultGenerationControllerV7TriggerOMa
+ _$sSo14NSUserDefaultsC14SuggestedImageE06daemonB0ABvgZ
+ _$syXlN
+ _CFPreferencesAppSynchronize
+ _CFPreferencesCopyAppValue
+ _CFPreferencesSetAppValue
+ _OBJC_CLASS_$_LSApplicationRecord
+ _OBJC_CLASS_$_NSUserDefaults
+ _OBJC_CLASS_$__PosterBoardServices
+ _kCFBooleanFalse
+ _kCFBooleanTrue
+ _objc_release_x26
+ _objc_retain_x22
- _$s14SuggestedImage27DefaultGenerationControllerV06handleD8Requests3for15progressHandleryAA7UseCaseOSg_yAA0D13ProgressEventOYbcSgtYaKF
- _$s14SuggestedImage27DefaultGenerationControllerV06handleD8Requests3for15progressHandleryAA7UseCaseOSg_yAA0D13ProgressEventOYbcSgtYaKFTu
CStrings:
+ "Error refreshing poster descriptors after install-state change: %@"
+ "Install state changed; refreshing poster descriptors"
+ "Install state unchanged; skipping poster refresh"
+ "Outside this device's generation window; deferring personalization production until next slot at %{public}s."
+ "Poster descriptors refreshed and install state persisted (isInstalled=%{bool}d)"
+ "PosterUpdateOnInstallChange"
+ "Probing Image Playground app install state: isInstalled=%{bool}d, previous=%s"
+ "com.apple.GenerativePlaygroundApp"
+ "com.apple.Posters.ImagePlaygroundPosterApp.ImagePlaygroundPoster"
+ "initWithBundleIdentifier:allowPlaceholder:error:"
+ "lastKnownIPAppInstallState"
+ "refreshPosterDescriptorsForExtension:completion:"
```
