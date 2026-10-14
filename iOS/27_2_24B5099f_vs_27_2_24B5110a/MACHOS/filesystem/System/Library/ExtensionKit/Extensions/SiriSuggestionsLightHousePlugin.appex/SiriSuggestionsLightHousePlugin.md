## SiriSuggestionsLightHousePlugin

> `/System/Library/ExtensionKit/Extensions/SiriSuggestionsLightHousePlugin.appex/SiriSuggestionsLightHousePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15f8` | `0xf84` | **`-0x674`** |
| `__TEXT.__auth_stubs` | `0x2b0` | `0x220` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x130` | `0xa8` | **`-0x88`** |
| `__TEXT.__oslogstring` | `0x141` | `0xd1` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x158` | `0x110` | **`-0x48`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xc0` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0xc` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x10` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3605.6.1.0.0
+3605.7.1.0.0

-  - /System/Library/PrivateFrameworks/SiriRemembers.framework/SiriRemembers

-  - /System/Library/PrivateFrameworks/SiriSuggestionsIntelligence.framework/SiriSuggestionsIntelligence

-  Functions: 47
-  Symbols:   63
-  CStrings:  6
+  Functions: 32
+  Symbols:   59
+  CStrings:  4
Symbols:
+ _swift_release_x24
- _swift_errorRelease
- _swift_release_x19
- _swift_release_x20
- _swift_release_x21
- _swift_release_x8
CStrings:
- "error running the lighthouse plugin"
- "running DefaultConversionLogger from lighthouse plugin"
```
