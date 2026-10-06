## BiomeSELFIngestor

> `/System/Library/ExtensionKit/Extensions/BiomeSELFIngestor.appex/BiomeSELFIngestor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6538` | `0x4b74` | **`-0x19c4`** |
| `__TEXT.__auth_stubs` | `0x640` | `0x5b0` | **`-0x90`** |
| `__TEXT.__eh_frame` | `0x188` | `0x118` | **`-0x70`** |
| `__TEXT.__swift5_typeref` | `0x1d1` | `0x16d` | **`-0x64`** |
| `__DATA_CONST.__const` | `0x6a0` | `0x650` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0x328` | `0x2e0` | **`-0x48`** |
| `__DATA.__data` | `0xd8` | `0xa0` | **`-0x38`** |
| `__TEXT.__cstring` | `0x229` | `0x1f9` | **`-0x30`** |
| `__TEXT.__const` | `0x1ea` | `0x1c2` | **`-0x28`** |
| `__DATA_CONST.__got` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xc0` | `0xa8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x120` | `0x108` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0xc` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-2.4.4.0.0
+2.4.5.0.0

-  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary

-  Functions: 65
-  Symbols:   78
-  CStrings:  18
+  Functions: 61
+  Symbols:   74
+  CStrings:  17
Symbols:
+ _objc_release_x26
- _OBJC_CLASS_$_BMIntelligenceFlowTranscriptDatastreamEvent
- _objc_retain_x26
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_release_x20
CStrings:
- "IntelligenceFlow.Transcript.Datastream"
```
