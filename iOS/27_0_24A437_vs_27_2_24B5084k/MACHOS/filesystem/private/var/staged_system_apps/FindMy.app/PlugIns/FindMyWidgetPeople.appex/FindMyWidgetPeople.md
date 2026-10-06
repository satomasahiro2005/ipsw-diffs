## FindMyWidgetPeople

> `/private/var/staged_system_apps/FindMy.app/PlugIns/FindMyWidgetPeople.appex/FindMyWidgetPeople`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x336d4` | `0x291e4` | **`-0xa4f0`** |
| `__DATA.__bss` | `0x1dc8` | `0x15d8` | **`-0x7f0`** |
| `__TEXT.__eh_frame` | `0x106c` | `0x9fc` | **`-0x670`** |
| `__TEXT.__auth_stubs` | `0x22c0` | `0x1e10` | **`-0x4b0`** |
| `__TEXT.__const` | `0x23c4` | `0x1f14` | **`-0x4b0`** |
| `__DATA.__data` | `0x1c98` | `0x1838` | **`-0x460`** |
| `__DATA_CONST.__auth_ptr` | `0xa88` | `0x800` | **`-0x288`** |
| `__TEXT.__unwind_info` | `0xb88` | `0x928` | **`-0x260`** |
| `__DATA_CONST.__auth_got` | `0x1168` | `0xf10` | **`-0x258`** |
| `__TEXT.__swift5_typeref` | `0x28b8` | `0x26cc` | **`-0x1ec`** |
| `__DATA_CONST.__got` | `0x598` | `0x490` | **`-0x108`** |
| `__TEXT.__swift5_reflstr` | `0x8f0` | `0x825` | **`-0xcb`** |
| `__TEXT.__swift5_assocty` | `0x300` | `0x248` | **`-0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0xa08` | `0x950` | **`-0xb8`** |
| `__TEXT.__oslogstring` | `0x30e` | `0x25e` | **`-0xb0`** |
| `__TEXT.__constg_swiftt` | `0xbc8` | `0xb1c` | **`-0xac`** |
| `__TEXT.__cstring` | `0x910` | `0x880` | **`-0x90`** |
| `__DATA_CONST.__const` | `0xf98` | `0xf40` | **`-0x58`** |
| `__TEXT.__swift_as_ret` | `0x94` | `0x4c` | **`-0x48`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x3c` | **`-0x44`** |
| `__TEXT.__swift5_proto` | `0xe4` | `0xa4` | **`-0x40`** |
| `__TEXT.__swift_as_cont` | `0xa0` | `0x64` | **`-0x3c`** |
| `__DATA.__common` | `0x108` | `0xd8` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x1ac` | `0x17c` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0xd8` | `0xc8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-470.30.6.14.34
+470.31.6.16.26

-  Functions: 931
-  Symbols:   185
-  CStrings:  99
+  Functions: 780
+  Symbols:   181
+  CStrings:  88
Symbols:
+ __swiftEmptySetSingleton
+ _objc_release_x25
+ _objc_retain_x27
+ _swift_setDeallocating
- __swiftEmptyDictionarySingleton
- _bzero
- _objc_release
- _objc_retain_x23
- _objc_retain_x24
- _swift_release_x12
- _swift_retain_x20
- _swift_unknownObjectRelease
CStrings:
- "%s"
- "%s - did receive fetchWithOptions: %s"
- "%s - error: %{public}@"
- "%s - ids: %{public}s"
- "%s - result %s"
- "%s - will call fetchWithOptions: %s"
- "PERSON_ENTITY_TITLE"
- "WidgetPersonEntityQuery"
- "com.apple.findmy"
- "customDefaultResult()"
- "fetchModels(options:)"
```
