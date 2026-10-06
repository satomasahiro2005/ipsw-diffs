## managedappsd

> `/usr/libexec/managedappsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11a0` | `0x1364` | **`+0x1c4`** |
| `__TEXT.__auth_stubs` | `0x300` | `0x360` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x188` | `0x1b8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x63` | `0x93` | **`+0x30`** |
| `__TEXT.__const` | `0x52` | `0x62` | **`+0x10`** |
| `__DATA.__data` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xd` | `0x15` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-113.2.5.0.0
+113.40.17.0.0

-  Symbols:   68
-  CStrings:  8
+  Symbols:   76
+  CStrings:  9
Symbols:
+ _$sSS10describingSSx_tclufC
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _$ss5ErrorMp
+ _$sypN
+ _exit
+ _objc_release_x26
+ _swift_arrayDestroy
+ _swift_errorRelease
+ _swift_errorRetain
- _swift_errorInMain
Functions:
~ sub_100000d60 : 1792 -> 2244
~ sub_100001d0c -> sub_100001ed0 : 68 -> 84
~ sub_100001d50 -> sub_100001f24 : 84 -> 68
CStrings:
+ "%s failed to set up services: %{public}s"
```
