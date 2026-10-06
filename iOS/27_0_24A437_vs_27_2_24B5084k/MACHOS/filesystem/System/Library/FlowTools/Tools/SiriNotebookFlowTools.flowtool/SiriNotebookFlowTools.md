## SiriNotebookFlowTools

> `/System/Library/FlowTools/Tools/SiriNotebookFlowTools.flowtool/SiriNotebookFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54e94` | `0x52640` | **`-0x2854`** |
| `__TEXT.__eh_frame` | `0x3c40` | `0x3600` | **`-0x640`** |
| `__TEXT.__auth_stubs` | `0x15c0` | `0x1710` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x1660` | `0x1530` | **`-0x130`** |
| `__DATA_CONST.__auth_got` | `0xae8` | `0xb90` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x611` | `0x5b1` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0xbba` | `0xbfe` | **`+0x44`** |
| `__TEXT.__oslogstring` | `0x853` | `0x893` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x358` | `0x324` | **`-0x34`** |
| `__DATA.__data` | `0xc38` | `0xc68` | **`+0x30`** |
| `__TEXT.__const` | `0x2608` | `0x2638` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xf30` | `0xf58` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x1d0` | `0x1b4` | **`-0x1c`** |
| `__DATA_CONST.__got` | `0x448` | `0x458` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x244` | `0x254` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x66c` | `0x678` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xd8` | `0xdc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3600.28.20.0.0
+3605.11.1.0.0

-  Functions: 1893
-  Symbols:   145
-  CStrings:  125
+  Functions: 1907
+  Symbols:   147
+  CStrings:  123
Symbols:
+ _swift_beginAccess
+ _swift_release_x22
CStrings:
+ "[CreateListAddReminderFlowTool] 'type' parameter not found in ToolDefinition; omitting (will use default)"
+ "[PrepareReadReminderFlowTool] Resolved %ld list colour(s) of %ld"
+ "[PrepareReadReminderFlowTool] Resolved %ld reminder section name(s) across %ld list(s)"
- "%s: No enums conforming to %s-%s in bundleID: %s"
- "EntityCollectionEnabled"
- "[BaseCreateReminderFlowTool] No reminder available in the tool output"
- "[UpdateReminderFlowTool] No reminder available in the tool output"
- "enumTypeIdentifier(conforming:fromApp:onDevice:)"
```
