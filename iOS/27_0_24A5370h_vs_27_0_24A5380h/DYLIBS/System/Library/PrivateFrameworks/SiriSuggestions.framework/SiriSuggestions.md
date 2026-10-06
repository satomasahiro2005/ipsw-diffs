## SiriSuggestions

> `/System/Library/PrivateFrameworks/SiriSuggestions.framework/SiriSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19c110` | `0x19c298` | **`+0x188`** |
| `__DATA.__bss` | `0x69e0` | `0x6860` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x8680` | `0x8800` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0xa1b8` | `0xa278` | **`+0xc0`** |
| `__AUTH.__data` | `0x1b68` | `0x1ab0` | **`-0xb8`** |
| `__TEXT.__eh_frame` | `0x12118` | `0x120a8` | **`-0x70`** |
| `__TEXT.__oslogstring` | `0x7c3d` | `0x7c9d` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0xc1b8` | `0xc1d8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x480f` | `0x482f` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6998` | `0x6978` | **`-0x20`** |
| `__TEXT.__const` | `0xf078` | `0xf088` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x47a4` | `0x47b0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2910` | `0x2908` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x500e` | `0x5014` | **`+0x6`** |

### Other Changes

```diff

-3600.11.1.0.0
+3600.11.2.0.0

-  Functions: 9749
+  Functions: 9752

-  CStrings:  909
+  CStrings:  910
Symbols:
+ _symbolic SbSg
- _swift_willThrowTypedImpl
CStrings:
+ "LinwoodFallbackServiceRefresher: Linwood enablement changed to %{bool}d. Refreshing service."
+ "LinwoodFallbackServiceRefresher: Linwood enablement unchanged (%{bool}d). Skipping refresh."
- "LinwoodFallbackServiceRefresher: Linwood enablement changed. Refreshing service."
```
