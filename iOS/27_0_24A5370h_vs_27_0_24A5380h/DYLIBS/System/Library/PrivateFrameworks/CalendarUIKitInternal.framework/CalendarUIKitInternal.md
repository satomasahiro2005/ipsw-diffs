## CalendarUIKitInternal

> `/System/Library/PrivateFrameworks/CalendarUIKitInternal.framework/CalendarUIKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4acf4` | `0x4d9cc` | **`+0x2cd8`** |
| `__TEXT.__eh_frame` | `0x1118` | `0x1498` | **`+0x380`** |
| `__DATA_DIRTY.__data` | `0x800` | `0x8d0` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x570` | `0x620` | **`+0xb0`** |
| `__DATA.__bss` | `0x890` | `0x810` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x100` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x970` | `0x9e8` | **`+0x78`** |
| `__DATA.__data` | `0x5d8` | `0x568` | **`-0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1320` | `0x1388` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x478` | `0x428` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5e8` | `0x630` | **`+0x48`** |
| `__TEXT.__cstring` | `0x587` | `0x5c7` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xbce` | `0xc0a` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x710` | `0x738` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x13d0` | `0x13b0` | **`-0x20`** |
| `__TEXT.__const` | `0x12d8` | `0x12f8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x4e5` | `0x4c5` | **`-0x20`** |
| `__DATA.__common` | `0x38` | `0x20` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x70` | `0x88` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x8d8` | `0x8c8` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0xbd8` | `0xbd0` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x208` | `0x204` | **`-0x4`** |

### Other Changes

```diff

-1318.0.0.0.0
+1320.0.0.0.0

+  - /System/Library/Frameworks/Intents.framework/Intents

+  - /System/Library/PrivateFrameworks/MorphunSwift.framework/MorphunSwift

-  Functions: 816
-  Symbols:   720
-  CStrings:  61
+  Functions: 826
+  Symbols:   725
+  CStrings:  66
Symbols:
+ _OBJC_CLASS_$_INDateComponentsRange
+ _OBJC_CLASS_$_INRecurrenceRule
+ ___swift_closure_destructor.41Tm
+ _symbolic Sny_____G SS5IndexV
+ _symbolic _____Sg 12MorphunSwift20ConfigurableAnalyzerC
+ _symbolic _____Sg 12MorphunSwift5TokenV
+ _symbolic _____Sg 12SiriOntology21PayloadAttachmentInfoV
+ _symbolic _____Sg_ABt 12SiriOntology21PayloadAttachmentInfoV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12MorphunSwift20ConfigurationFeatureO
- ___swift_closure_destructor.43Tm
- ___swift_memcpy17_8
- ___swift_mutable_project_boxed_opaque_existential_1
- _swift_makeBoxUnique
CStrings:
+ "Error trying to get an analyzer for normalization: %@"
+ "SiriEventParser: Error thrown during parse: %@"
+ "SiriEventParser: Unexpected entity type in parse graph"
+ "dateTimeQualifier"
+ "definedDateTimeRange"
```
