## NotebookSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/NotebookSnippetProviderPlugin.bundle/NotebookSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24484` | `0x2debc` | **`+0x9a38`** |
| `__TEXT.__auth_stubs` | `0xff0` | `0x1240` | **`+0x250`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0x200` | **`+0x140`** |
| `__DATA_CONST.__auth_got` | `0x800` | `0x928` | **`+0x128`** |
| `__TEXT.__swift5_typeref` | `0x318` | `0x406` | **`+0xee`** |
| `__TEXT.__const` | `0xa30` | `0xb10` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x498` | `0x560` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0xabc` | `0xb68` | **`+0xac`** |
| `__DATA.__data` | `0x310` | `0x3b0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x520` | `0x5b0` | **`+0x90`** |
| `__DATA_CONST.__got` | `0x230` | `0x2b0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x963` | `0x9c3` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x208` | `0x260` | **`+0x58`** |
| `__DATA.__common` | `0xb8` | `0xc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.28.20.0.0
+3605.11.1.0.0

-  Functions: 569
-  Symbols:   120
-  CStrings:  57
+  Functions: 710
+  Symbols:   125
+  CStrings:  58
Symbols:
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __swiftEmptySetSingleton
+ _free
+ _swift_coroFrameAlloc
+ _swift_retain_x19
+ _swift_retain_x25
- _objc_release_x28
- _swift_retain_x24
CStrings:
+ "[ReminderSearchResultSnippetHandler] Entity-derived section groups for %ld list(s)"
```
