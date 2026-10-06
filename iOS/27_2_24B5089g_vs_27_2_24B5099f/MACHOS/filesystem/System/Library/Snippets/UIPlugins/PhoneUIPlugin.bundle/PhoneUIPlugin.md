## PhoneUIPlugin

> `/System/Library/Snippets/UIPlugins/PhoneUIPlugin.bundle/PhoneUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__text` | `0x3774` | `0x376c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.20.1.0.0
+3605.26.2.0.0

-  Symbols:   423
+  Symbols:   425
Symbols:
+ _$s14PhoneSnippetUI0aB10DataModelsO26emptyEmergencyConfirmationyAcA05EmptygH5ModelVcACmFWC
+ _objc_release_x19
+ _objc_release_x22
- _objc_release_x26
Functions:
~ _$s13PhoneUIPluginAAC7snippet3for4mode5idiom7SwiftUI7AnyViewV0a7SnippetH00aK10DataModelsO_So7VRXModeVSo8VRXIdiomVtKF : 8124 -> 8116
~ _OUTLINED_FUNCTION_8 : 24 -> 16
~ _OUTLINED_FUNCTION_10 : 16 -> 20
~ _OUTLINED_FUNCTION_15 : 28 -> 12
~ _OUTLINED_FUNCTION_16 : 12 -> 28
~ _OUTLINED_FUNCTION_19 : 20 -> 12
~ _OUTLINED_FUNCTION_23 : 20 -> 32
```
