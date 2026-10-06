## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94118` | `0x961a4` | **`+0x208c`** |
| `__TEXT.__const` | `0x7d60` | `0x7f40` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x78a8` | `0x79c0` | **`+0x118`** |
| `__DATA.__bss` | `0x53d0` | `0x54d0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1b98` | `0x1c18` | **`+0x80`** |
| `__DATA.__data` | `0x6b28` | `0x6b88` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x4574` | `0x45d4` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x31dc` | `0x3238` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x1c74` | `0x1cc4` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x200` | `0x240` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2090` | `0x20d0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x3bec` | `0x3bb4` | **`-0x38`** |
| `__TEXT.__swift5_reflstr` | `0x36fd` | `0x372d` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x38d8` | `0x38fe` | **`+0x26`** |
| `__DATA.__objc_const` | `0x5480` | `0x54a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1058` | `0x1078` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2400` | `0x2420` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x860` | `0x878` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0xa80` | `0xa88` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x144` | `0x14c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x430` | `0x438` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x31c` | `0x324` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2228` | `0x2230` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-53.0.0.0.0
+55.0.0.0.0

+  - /usr/lib/swift/libswift_DarwinFoundation1.dylib

-  Functions: 2864
-  Symbols:   940
-  CStrings:  1074
+  Functions: 2876
+  Symbols:   945
+  CStrings:  1079
Symbols:
+ _$s6Darwin5errnos5Int32Vvg
+ _AECoreErrorUserInfo
+ _AECoreNotAliveParticipantPIDsKey
+ _kill
+ _swift_release_x12
CStrings:
+ "/System/Library/PrivateFrameworks/DeviceCheckInternal.framework/devicecheckd"
+ "/usr/libexec/trustd"
+ "Refusing to start session — participant PIDs not alive: %{public}s"
+ "com.apple.CharacterPaletteIM"
+ "pid"
```
