## RemindersWidgetExtension

> `/private/var/staged_system_apps/Reminders.app/PlugIns/RemindersWidgetExtension.appex/RemindersWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd07e8` | `0xd1818` | **`+0x1030`** |
| `__TEXT.__eh_frame` | `0x25c0` | `0x2848` | **`+0x288`** |
| `__TEXT.__objc_methname` | `0x6ca` | `0x63a` | **`-0x90`** |
| `__TEXT.__objc_stubs` | `0x8c0` | `0x840` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x2680` | `0x26f0` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xcd8` | `0xd20` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x3b20` | `0x3b50` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x230` | `0x210` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x17c` | `0x19c` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1d98` | `0x1db0` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__DATA.__data` | `0x50e8` | `0x50f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-4034.15.0.0.0
+4037.1.0.0.0

-  Functions: 3233
-  Symbols:   232
-  CStrings:  392
+  Functions: 3246
+  Symbols:   233
+  CStrings:  388
Symbols:
+ _OBJC_CLASS_$_REMReminderFetchOptions
CStrings:
+ "defaultFetchOptions"
- "fetchCustomSmartListWithObjectID:error:"
- "fetchListWithObjectID:error:"
- "fetchReminderWithObjectID:error:"
- "fetchRemindersWithError:"
- "fetchRemindersWithObjectIDs:error:"
```
