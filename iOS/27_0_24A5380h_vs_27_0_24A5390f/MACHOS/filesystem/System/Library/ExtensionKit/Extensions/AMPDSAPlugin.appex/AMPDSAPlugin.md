## AMPDSAPlugin

> `/System/Library/ExtensionKit/Extensions/AMPDSAPlugin.appex/AMPDSAPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae48` | `0xa8cc` | **`-0x57c`** |
| `__DATA.__bss` | `0xd80` | `0xa80` | **`-0x300`** |
| `__TEXT.__const` | `0x918` | `0x778` | **`-0x1a0`** |
| `__DATA_CONST.__const` | `0x618` | `0x520` | **`-0xf8`** |
| `__TEXT.__eh_frame` | `0x650` | `0x598` | **`-0xb8`** |
| `__TEXT.__oslogstring` | `0x505` | `0x4b5` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x328` | `0x2e0` | **`-0x48`** |
| `__TEXT.__auth_stubs` | `0xb30` | `0xaf0` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x114` | `0xd4` | **`-0x40`** |
| `__DATA.__data` | `0x260` | `0x228` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x232` | `0x200` | **`-0x32`** |
| `__TEXT.__cstring` | `0x231` | `0x261` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1ac` | `0x180` | **`-0x2c`** |
| `__DATA.__objc_const` | `0xb8` | `0x90` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x5a0` | `0x580` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x6c` | `0x54` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x40` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x46` | `0x37` | **`-0xf`** |
| `__DATA_CONST.__auth_ptr` | `0x210` | `0x218` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x215` | `0x20d` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x15` | `0x14` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-35.0.0.0.0
+38.0.0.0.0

-  Functions: 210
-  Symbols:   120
+  Functions: 189
+  Symbols:   119
Symbols:
- _objc_allocWithZone
CStrings:
+ ",\n    modelName: "
+ "AMPDSAHyperParams(\n    taskType: "
+ "task_type"
- "AMPDSAHyperParams(\n    modelName: "
- "Failed to decode AMPDSACustomTaskParameters from PluginPreference: %@"
- "taskParameters"
```
