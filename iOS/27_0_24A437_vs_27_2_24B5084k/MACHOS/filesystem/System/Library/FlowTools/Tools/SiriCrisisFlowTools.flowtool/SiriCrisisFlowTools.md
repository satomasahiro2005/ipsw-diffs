## SiriCrisisFlowTools

> `/System/Library/FlowTools/Tools/SiriCrisisFlowTools.flowtool/SiriCrisisFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16bdc` | `0x19ff0` | **`+0x3414`** |
| `__DATA.__bss` | `0x880` | `0xd00` | **`+0x480`** |
| `__TEXT.__const` | `0x14d8` | `0x17f8` | **`+0x320`** |
| `__TEXT.__eh_frame` | `0x988` | `0xb98` | **`+0x210`** |
| `__TEXT.__auth_stubs` | `0xe40` | `0x1030` | **`+0x1f0`** |
| `__DATA.__data` | `0xe68` | `0xfe8` | **`+0x180`** |
| `__TEXT.__swift5_typeref` | `0x45c` | `0x56c` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x489` | `0x589` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x710` | `0x810` | **`+0x100`** |
| `__DATA.__objc_const` | `0xbb0` | `0xca8` | **`+0xf8`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x820` | **`+0xf8`** |
| `__DATA_CONST.__const` | `0xd88` | `0xe48` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x55a` | `0x60a` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x60c` | `0x6b0` | **`+0xa4`** |
| `__DATA_CONST.__auth_ptr` | `0x5a0` | `0x628` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x210` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1170` | `0x11d0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x287` | `0x2d0` | **`+0x49`** |
| `__TEXT.__objc_classname` | `0x6e7` | `0x727` | **`+0x40`** |
| `__DATA.__common` | `0x1c0` | `0x1f0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x90` | `0xb4` | **`+0x24`** |
| `__TEXT.__cstring` | `0x8df` | `0x8ff` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x64` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x54` | `0x6c` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x80` | `0x88` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3600.12.16.0.0
+3605.4.1.0.0

+  - /System/Library/PrivateFrameworks/CrisisResources.framework/CrisisResources

+  - /System/Library/PrivateFrameworks/ToolKit.framework/ToolKit

-  Functions: 647
-  Symbols:   144
-  CStrings:  156
+  Functions: 732
+  Symbols:   149
+  CStrings:  166
Symbols:
+ _objc_release_x26
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRelease_n
CStrings:
+ "Failed to serialize crisis resource %s; skipping: %s"
+ "No country resolved for [%s]; returning no resources"
+ "No resources for [%s] in %s"
+ "Resource lookup failed: %s"
+ "Skipping crisis resource %s with no resolvable name"
+ "_TtC19SiriCrisisFlowTools26GetCrisisResourcesFlowTool"
+ "_resourceCategories"
+ "com.apple.siri.SiriCrisisAppIntentsExtension"
+ "com.apple.siri.crisis"
+ "resolveCountryCode"
+ "resourcesProvider"
- "com.apple.siri.SiriCrisisFlowTools"
```
