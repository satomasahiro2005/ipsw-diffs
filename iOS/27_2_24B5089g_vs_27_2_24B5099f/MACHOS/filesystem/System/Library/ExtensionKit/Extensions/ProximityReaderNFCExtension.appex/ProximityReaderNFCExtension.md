## ProximityReaderNFCExtension

> `/System/Library/ExtensionKit/Extensions/ProximityReaderNFCExtension.appex/ProximityReaderNFCExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cf0` | `0x4274` | **`-0xa7c`** |
| `__TEXT.__eh_frame` | `0x380` | `0x140` | **`-0x240`** |
| `__TEXT.__unwind_info` | `0x180` | `0x120` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x188` | `0x1d8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x670` | `0x6b0` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x50` | `0x7c` | **`+0x2c`** |
| `__TEXT.__const` | `0x1ba` | `0x192` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0xe4` | `0x107` | **`+0x23`** |
| `__DATA.__objc_const` | `0x390` | `0x3b0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x340` | `0x360` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1db` | `0x1f4` | **`+0x19`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x4` | **`-0x14`** |
| `__DATA.__data` | `0x240` | `0x230` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x90` | `0x80` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x4` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x355` | `0x364` | **`+0xf`** |
| `__TEXT.__swift5_reflstr` | `0x25` | `0x34` | **`+0xf`** |
| `__TEXT.__swift5_fieldmd` | `0x28` | `0x34` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x8` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x80` | `0x78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-151.2.0.0.0
+151.5.0.0.0

-  Functions: 60
-  Symbols:   90
-  CStrings:  120
+  Functions: 53
+  Symbols:   94
+  CStrings:  121
Symbols:
+ __Block_copy
+ __Block_release
+ _objc_release
+ _swift_beginAccess
+ _swift_release_x21
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_retain_x23
+ _swift_retain_x27
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
- _swift_allocError
- _swift_continuation_await
- _swift_continuation_init
- _swift_continuation_throwingResume
- _swift_continuation_throwingResumeWithError
- _swift_release_x19
- _swift_release_x23
- _swift_release_x25
- _swift_retain_x8
- _swift_willThrow
CStrings:
+ "Posted notification for %s, actionable: %{bool}d"
+ "linkController"
- "Posted notification for %s"
```
