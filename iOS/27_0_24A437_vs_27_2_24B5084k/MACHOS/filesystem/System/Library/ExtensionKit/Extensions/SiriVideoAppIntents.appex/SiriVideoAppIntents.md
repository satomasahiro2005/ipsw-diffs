## SiriVideoAppIntents

> `/System/Library/ExtensionKit/Extensions/SiriVideoAppIntents.appex/SiriVideoAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17654` | `0x19f44` | **`+0x28f0`** |
| `__TEXT.__oslogstring` | `0x24e` | `0x48e` | **`+0x240`** |
| `__TEXT.__const` | `0x3e6e` | `0x3ffe` | **`+0x190`** |
| `__DATA.__bss` | `0x6680` | `0x6800` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0xd80` | `0xed0` | **`+0x150`** |
| `__DATA_CONST.__auth_got` | `0x6c0` | `0x768` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x11be` | `0x1258` | **`+0x9a`** |
| `__DATA_CONST.__const` | `0xfd8` | `0x1040` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0xa90` | `0xaf0` | **`+0x60`** |
| `__DATA.__data` | `0xb98` | `0xbe0` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x410` | `0x450` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x758` | `0x78c` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x168` | `0x190` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x658` | `0x678` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x6b8` | `0x6d8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x4b4` | `0x4d0` | **`+0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x8ff` | `0x913` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x334` | `0x340` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x68` | `0x6c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x38` | `0x3c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__cstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3600.28.7.0.0
+3605.20.2.0.0

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 957
-  Symbols:   78
-  CStrings:  38
+  Functions: 985
+  Symbols:   87
+  CStrings:  46
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _objc_release_x19
+ _objc_release_x23
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_retain
+ _swift_retain_n
+ _swift_retain_x19
CStrings:
+ "FindContentIntentValueQuery produced %ld items from %ld search results"
+ "FindContentIntentValueQuery: added TV episode entity: %s"
+ "FindContentIntentValueQuery: added TV season entity: %s"
+ "FindContentIntentValueQuery: added TV show entity: %s"
+ "FindContentIntentValueQuery: added movie entity: %s"
+ "FindContentIntentValueQuery: added person entity: %s"
+ "FindContentIntentValueQuery: no privateSearchResult found in VideoSearch"
+ "FindContentIntentValueQuery: skipping cast/crew member '%s' with nil canonicalID"
+ "FindContentIntentValueQuery: skipping unknown content type"
+ "FindContentIntentValueQuery: skipping unsupported content type"
+ "person"
- "No privateSearchResult found in VideoSearch"
- "Skipping unknown content type"
- "Skipping unsupported content type"
```
