## PhoneUIPlugin

> `/System/Library/Snippets/UIPlugins/PhoneUIPlugin.bundle/PhoneUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x376c` | `0x3978` | **`+0x20c`** |
| `__TEXT.__auth_stubs` | `0x6c0` | `0x6e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x208` | `0x220` | **`+0x18`** |
| `__DATA.__data` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x360` | `0x370` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.26.2.0.0
+3605.27.1.0.0

-  Functions: 85
-  Symbols:   425
+  Functions: 87
+  Symbols:   433
Symbols:
+ _$s14PhoneSnippetUI0aB10DataModelsO18contactCompositionyAcA07ContactG5ModelVcACmFWC
+ _$s14PhoneSnippetUI22ContactCompositionViewV05SwiftC00F0AAMc
+ _$s14PhoneSnippetUI22ContactCompositionViewV5modelAcA0dE5ModelV_tcfC
+ _$s14PhoneSnippetUI22ContactCompositionViewVAC05SwiftC00F0AAWL
+ _$s14PhoneSnippetUI22ContactCompositionViewVMa
+ _$s14PhoneSnippetUI23ContactCompositionModelVMa
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$s7SwiftUI9EmptyViewVAcA0D0AAWL
+ _$s7SwiftUI9EmptyViewVAcA0D0AAWl
+ _OUTLINED_FUNCTION_25
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _objc_release_x22
Functions:
~ _$s13PhoneUIPluginAAC7snippet3for4mode5idiom7SwiftUI7AnyViewV0a7SnippetH00aK10DataModelsO_So7VRXModeVSo8VRXIdiomVtKF : 8116 -> 8544
+ _$s7SwiftUI9EmptyViewVAcA0D0AAWl
~ _OUTLINED_FUNCTION_6 : 16 -> 24
~ _OUTLINED_FUNCTION_10 : 20 -> 16
~ _OUTLINED_FUNCTION_12 : 32 -> 20
~ _OUTLINED_FUNCTION_15 : 12 -> 32
~ _OUTLINED_FUNCTION_23 : 32 -> 12
~ _OUTLINED_FUNCTION_24 : 24 -> 20
+ _OUTLINED_FUNCTION_25
```
