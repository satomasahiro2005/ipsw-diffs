## PhoneUIPlugin

> `/System/Library/Snippets/UIPlugins/PhoneUIPlugin.bundle/PhoneUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3454` | `0x3774` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0xb7` | `0xe7` | **`+0x30`** |
| `__TEXT.__cstring` | `0x21` | `0x49` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x6a0` | `0x6b0` | **`+0x10`** |
| `__DATA.__data` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x350` | `0x358` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.38.22.11.2
+3605.17.1.1.1

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/PrivateFrameworks/IntelligencePlatform.framework/IntelligencePlatform

-  Functions: 84
-  Symbols:   415
-  CStrings:  7
+  Functions: 85
+  Symbols:   423
+  CStrings:  9
Symbols:
+ _$s14PhoneSnippetUI0aB10DataModelsO21emergencyConfirmationyAcA09EmergencyG5ModelVcACmFWC
+ _$s14PhoneSnippetUI0aB10DataModelsOACSEAAWL
+ _$s14PhoneSnippetUI0aB10DataModelsOACSEAAWlTm
+ _$s14PhoneSnippetUI0aB10DataModelsOSEAAMc
+ _$s7SwiftUI9EmptyViewVAA0D0AAWP
+ _$s7SwiftUI9EmptyViewVN
+ _$sSE20IntelligencePlatformE12asJSONStringSSvg
+ _OUTLINED_FUNCTION_23
+ _OUTLINED_FUNCTION_24
+ _objc_release_x26
+ _swift_release_x19
+ _swift_retain_x19
- _$s14PhoneSnippetUI34ContactAndHandleDisambiguationViewVAC05SwiftC00H0AAWlTm
- _$ss27_diagnoseUnexpectedEnumCase4types5NeverOxm_tlF
- _swift_release_x22
- _swift_retain_x22
CStrings:
+ "#PhoneUIPlugin %s missing case for %s"
+ "snippet(for:mode:idiom:)"
```
