## SiriNotebookFlowTools

> `/System/Library/FlowTools/Tools/SiriNotebookFlowTools.flowtool/SiriNotebookFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dafc` | `0x54e28` | **`+0x732c`** |
| `__TEXT.__eh_frame` | `0x39f0` | `0x3c60` | **`+0x270`** |
| `__TEXT.__auth_stubs` | `0x14e0` | `0x15c0` | **`+0xe0`** |
| `__DATA_CONST.__auth_got` | `0xa78` | `0xae8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1600` | `0x1670` | **`+0x70`** |
| `__TEXT.__cstring` | `0x5b1` | `0x611` | **`+0x60`** |
| `__DATA.__data` | `0xbf0` | `0xc38` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0xb88` | `0xbba` | **`+0x32`** |
| `__DATA_CONST.__got` | `0x418` | `0x448` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x378` | `0x358` | **`-0x20`** |
| `__TEXT.__const` | `0x2618` | `0x2608` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x843` | `0x853` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0xd8` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x1dc` | `0x1d0` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xe60` | `0xe68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.28.13.0.0
+3600.28.20.0.0

-  Functions: 1829
-  Symbols:   143
-  CStrings:  123
+  Functions: 1893
+  Symbols:   145
+  CStrings:  125
Symbols:
+ _swift_bridgeObjectRelease_n
+ _swift_release_x12
CStrings:
+ "[ReminderFlowTool] AppIntent not found [bundleID=%s, kind=%s, onDevice=%s]"
+ "com.apple.NanoReminders"
+ "com.apple.reminders"
+ "entityTypeIdentifier(conforming:fromApp:onDevice:)"
+ "enumTypeIdentifier(conforming:fromApp:onDevice:)"
- "[ReminderFlowTool] AppIntent not found [bundleID=%s, kind=%s]"
- "entityTypeIdentifier(conforming:fromApp:)"
- "enumTypeIdentifier(conforming:fromApp:)"
```
