## WritingToolsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/WritingToolsAppIntentsExtension.appex/WritingToolsAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7512c` | `0x7c7cc` | **`+0x76a0`** |
| `__DATA.__data` | `0x7c28` | `0x8178` | **`+0x550`** |
| `__TEXT.__eh_frame` | `0x2e30` | `0x30c8` | **`+0x298`** |
| `__TEXT.__oslogstring` | `0x10e5` | `0x1235` | **`+0x150`** |
| `__TEXT.__const` | `0x8534` | `0x8654` | **`+0x120`** |
| `__TEXT.__constg_swiftt` | `0x41dc` | `0x42f0` | **`+0x114`** |
| `__TEXT.__unwind_info` | `0x1fb8` | `0x2080` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x26d0` | `0x2790` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0x20dc` | `0x215c` | **`+0x80`** |
| `__TEXT.__cstring` | `0x17f6` | `0x1866` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x2168` | `0x21d8` | **`+0x70`** |
| `__DATA.__objc_const` | `0x2ac0` | `0x2b20` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1370` | `0x13d0` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x248e` | `0x24c2` | **`+0x34`** |
| `__TEXT.__swift5_fieldmd` | `0x1ac4` | `0x1af4` | **`+0x30`** |
| `__DATA.__bss` | `0xb720` | `0xb740` | **`+0x20`** |
| `__DATA.__common` | `0x390` | `0x3a8` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x188` | `0x1a0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xfb0` | `0xfa0` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xdc` | `0xe8` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x818` | `0x820` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc8` | `0xcc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-151.1.6.0.0
+151.1.9.0.0

-  Functions: 2672
-  Symbols:   291
-  CStrings:  614
+  Functions: 2742
+  Symbols:   293
+  CStrings:  623
Symbols:
+ _swift_dynamicCastClass
+ _swift_weakAssign
CStrings:
+ "Adopted live rewrite session for follow-up (rdar://187409996); routing via .selectFollowUp"
+ "Could not adopt live rewrite session for follow-up: %@"
+ "DebugForceUnsafeOutput"
+ "No live follow-up matches open-ended prompt; using OEC/OEA path"
+ "Writing Tools aren’t designed to generate this type of content."
+ "__citations"
+ "_advisoriesToShow"
+ "_suppressedAdvisoryIDs"
+ "forgetHistory: clearing %ld version(s) — session closed"
+ "markFollowUpsAsSeen failed (non-fatal): %@"
- "_citations"
```
