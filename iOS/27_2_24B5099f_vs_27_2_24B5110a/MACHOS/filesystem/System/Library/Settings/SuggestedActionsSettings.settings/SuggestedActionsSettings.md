## SuggestedActionsSettings

> `/System/Library/Settings/SuggestedActionsSettings.settings/SuggestedActionsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaad0` | `0x8fd4` | **`-0x1afc`** |
| `__TEXT.__eh_frame` | `0x6f4` | `0x50c` | **`-0x1e8`** |
| `__TEXT.__swift5_typeref` | `0x518` | `0x3fc` | **`-0x11c`** |
| `__DATA_CONST.__const` | `0x2f8` | `0x258` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x39b` | `0x30b` | **`-0x90`** |
| `__TEXT.__unwind_info` | `0x3b8` | `0x338` | **`-0x80`** |
| `__TEXT.__const` | `0x504` | `0x494` | **`-0x70`** |
| `__TEXT.__swift5_capture` | `0xc4` | `0x74` | **`-0x50`** |
| `__DATA.__objc_const` | `0x210` | `0x1f0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x9c` | `0xbc` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x4c` | `0x30` | **`-0x1c`** |
| `__DATA.__data` | `0x508` | `0x4f0` | **`-0x18`** |
| `__TEXT.__objc_methname` | `0x7c` | `0x64` | **`-0x18`** |
| `__DATA.__bss` | `0x2d8` | `0x2c8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x900` | `0x8f0` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x2c` | `0x1c` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x480` | `0x478` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1b8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x14` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-21.0.0.0.0
+22.0.0.0.0

-  Functions: 281
-  Symbols:   106
-  CStrings:  36
+  Functions: 232
+  Symbols:   107
+  CStrings:  32
Symbols:
+ _swift_release_x24
+ _swift_retain_x20
+ _swift_retain_x26
- _swift_release_x19
- _swift_retain_x23
CStrings:
- "Hide Unused Suggestions"
- "To unhide a suggestion, turn it off and back on."
- "Unable to write hide unused suggestions: "
- "_hideUnusedSuggestions"
```
