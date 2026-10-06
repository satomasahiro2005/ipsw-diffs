## JournalWidgets

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalWidgets.appex/JournalWidgets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x552c8` | `0x55260` | **`-0x68`** |
| `__TEXT.__const` | `0x6194` | `0x61e4` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x135c` | `0x1384` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x14c` | `0x160` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x108` | `0x11c` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0xd90` | `0xd98` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x13a0` | `0x13a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-89.0.0.0.0
+94.0.0.0.0

-  Functions: 1763
-  Symbols:   149
+  Functions: 1764
+  Symbols:   148
Symbols:
- _swift_retain_x21
CStrings:
+ "Show or don’t show AI-generated writing prompts."
+ "settings-navigation://com.apple.Settings.Apps/com.apple.journal#showFollowupPrompts"
- "Show or don’t show AI generated writing prompts."
- "settings-navigation://com.apple.Settings.Apps/com.apple.journal#showWritingPrompts"
```
