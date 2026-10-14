## CrisisResourceUIPlugin

> `/System/Library/Snippets/UIPlugins/CrisisResourceUIPlugin.bundle/CrisisResourceUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7290` | `0xa9bc` | **`+0x372c`** |
| `__TEXT.__auth_stubs` | `0x9b0` | `0xcf0` | **`+0x340`** |
| `__TEXT.__eh_frame` | `0xf0` | `0x350` | **`+0x260`** |
| `__DATA_CONST.__auth_got` | `0x4e0` | `0x680` | **`+0x1a0`** |
| `__DATA.__data` | `0x450` | `0x590` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x34b` | `0x423` | **`+0xd8`** |
| `__TEXT.__const` | `0x5a4` | `0x674` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x248` | `0x308` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x128` | `0x1c8` | **`+0xa0`** |
| `__DATA.__bss` | `0x690` | `0x710` | **`+0x80`** |
| `__TEXT.__cstring` | `0x22c` | `0x28f` | **`+0x63`** |
| `__DATA_CONST.__const` | `0x361` | `0x3b1` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0xe4` | `0x124` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x280` | `0x2b0` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x2c` | `0x58` | **`+0x2c`** |
| `__TEXT.__constg_swiftt` | `0x144` | `0x16c` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x15c` | `0x184` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0xbd` | `0xd6` | **`+0x19`** |
| `__TEXT.__swift_as_cont` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`

### Other Changes

```diff

-3605.10.2.0.0
+3605.11.1.11.1
+  - /System/Library/Frameworks/AppIntents.framework/AppIntents

+  - /System/Library/Frameworks/Intents.framework/Intents

+  - /System/Library/PrivateFrameworks/IntelligenceFlow.framework/IntelligenceFlow

+  - /System/Library/PrivateFrameworks/ToolKit.framework/ToolKit

-  Functions: 186
-  Symbols:   99
-  CStrings:  33
+  Functions: 250
+  Symbols:   116
+  CStrings:  37
Symbols:
+ _OBJC_CLASS_$_INPerson
+ _objc_retain_x9
+ _swift_allocError
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_errorRetain
+ _swift_getEnumCaseMultiPayload
+ _swift_getObjCClassMetadata
+ _swift_getTupleTypeMetadata2
+ _swift_release_x24
+ _swift_release_x8
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
CStrings:
+ "Crisis card: cannot build message draft: %{public}s"
+ "com.apple.MobileSMS"
+ "com.apple.siri.crisis.TextCrisisResource"
+ "number keyword "
```
