## SiriSuggestions

> `/System/Library/PrivateFrameworks/SiriSuggestions.framework/SiriSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19ad30` | `0x19c110` | **`+0x13e0`** |
| `__TEXT.__oslogstring` | `0x79fd` | `0x7c3d` | **`+0x240`** |
| `__DATA.__bss` | `0x67e0` | `0x69e0` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x11f30` | `0x12118` | **`+0x1e8`** |
| `__AUTH_CONST.__objc_const` | `0xc080` | `0xc1b8` | **`+0x138`** |
| `__TEXT.__const` | `0xef48` | `0xf078` | **`+0x130`** |
| `__AUTH.__data` | `0x1ab0` | `0x1b68` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x6908` | `0x6998` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x478f` | `0x480f` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x4758` | `0x47a4` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x56a4` | `0x56e0` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x28f0` | `0x2910` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0xcb8` | `0xcd8` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x938` | `0x954` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x8fc` | `0x914` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0xa1a8` | `0xa1b8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x9b8` | `0x9c8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x5000` | `0x500e` | **`+0xe`** |
| `__DATA_CONST.__objc_classlist` | `0x6f8` | `0x700` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x540` | `0x544` | **`+0x4`** |

### Other Changes

```diff

-3600.5.1.0.0
+3600.11.1.0.0

-  Functions: 9677
-  Symbols:   2930
-  CStrings:  903
+  Functions: 9749
+  Symbols:   2938
+  CStrings:  909
Symbols:
+ _AFIsLinwoodEnabledAndAvailable
+ _OUTLINED_FUNCTION_263
+ _OUTLINED_FUNCTION_264
+ __DATA__TtC15SiriSuggestions31LinwoodFallbackServiceRefresher
+ __IVARS__TtC15SiriSuggestions31LinwoodFallbackServiceRefresher
+ __METACLASS_DATA__TtC15SiriSuggestions31LinwoodFallbackServiceRefresher
+ _symbolic _____ 15SiriSuggestions31LinwoodFallbackServiceRefresherC
+ _symbolic ______p 18SiriSuggestionsKit0B18ServiceRefreshableP
CStrings:
+ "Linwood is enabled. Setting up Linwood observer and returning NoOpSuggestionService."
+ "LinwoodFallbackServiceRefresher: BuildAutoCompleteIndex after service refresh. Added %ld phrases into the DB"
+ "LinwoodFallbackServiceRefresher: Error BuildAutoCompleteIndex after service refresh"
+ "LinwoodFallbackServiceRefresher: Linwood enablement changed. Refreshing service."
+ "LinwoodFallbackServiceRefresher: Linwood is enabled after refresh. Skipping index build."
+ "LinwoodFallbackServiceRefresher: initating index refresh post service refresh"
```
