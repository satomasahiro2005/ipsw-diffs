## TypeToSiriWidgetExtension

> `/Applications/Siri.app/PlugIns/TypeToSiriWidgetExtension.appex/TypeToSiriWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4adc` | `0x4b98` | **`+0xbc`** |
| `__TEXT.__objc_stubs` | `0xa0` | `0x100` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x53` | `0xa7` | **`+0x54`** |
| `__TEXT.__cstring` | `0x1ca` | `0x1ea` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x28` | `0x40` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x550` | `0x560` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe0` | `0xe8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 111
-  Symbols:   74
-  CStrings:  24
+  Functions: 113
+  Symbols:   75
+  CStrings:  28
Symbols:
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ _OBJC_CLASS_$_AFSystemAssistantExperienceStatusManager
- _AFIsLinwoodEnabledAndAvailable
CStrings:
+ "desiredOrchestrationModeIfEnabled"
+ "isLinwoodCapableAndEverAvailable"
+ "keyboard.badge.siri.gen1"
+ "keyboard.badge.siri.gen2"
+ "siriAvailability"
- "keyboard.badge.siri"
```
