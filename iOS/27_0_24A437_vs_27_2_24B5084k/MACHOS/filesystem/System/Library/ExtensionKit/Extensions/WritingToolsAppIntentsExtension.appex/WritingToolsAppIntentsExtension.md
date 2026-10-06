## WritingToolsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/WritingToolsAppIntentsExtension.appex/WritingToolsAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72c90` | `0x7512c` | **`+0x249c`** |
| `__TEXT.__eh_frame` | `0x2cb0` | `0x2e30` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x2bd8` | `0x2d38` | **`+0x160`** |
| `__TEXT.__swift5_typeref` | `0x2330` | `0x248e` | **`+0x15e`** |
| `__TEXT.__const` | `0x8424` | `0x8534` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x2068` | `0x2168` | **`+0x100`** |
| `__DATA.__data` | `0x7b78` | `0x7c28` | **`+0xb0`** |
| `__TEXT.__constg_swiftt` | `0x4148` | `0x41dc` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x1f28` | `0x1fb8` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x2650` | `0x26d0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x1095` | `0x10e5` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1330` | `0x1370` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0xf70` | `0xfb0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x760` | `0x7a0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1a8c` | `0x1ac4` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x467` | `0x49c` | **`+0x35`** |
| `__TEXT.__swift5_capture` | `0x1f4` | `0x224` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x20b7` | `0x20dc` | **`+0x25`** |
| `__DATA.__common` | `0x378` | `0x390` | **`+0x18`** |
| `__DATA.__bss` | `0xb710` | `0xb720` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x380` | `0x390` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x828` | `0x818` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x5cc` | `0x5d0` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x1c` | `0x20` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x190` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-149.104.0.0.0
+151.1.4.0.0

-  Functions: 2633
-  Symbols:   286
-  CStrings:  610
+  Functions: 2672
+  Symbols:   291
+  CStrings:  614
Symbols:
+ _WTWritingToolsPreservedAttributeName
+ _swift_isEscapingClosureAtFileLocation
+ _swift_makeBoxUnique
+ _swift_release_n
+ _swift_retain_n
CStrings:
+ "_rewritingClient"
+ "boolValue"
+ "editableRange: result=%s (cursor=%ld bounds=%s fullLength=%ld preserved=%ld)"
+ "enumerateAttribute:inRange:options:usingBlock:"
+ "v40@?0@8{_NSRange=QQ}16^B32"
- "_precomputedResultText"
```
