## applekeystored

> `/usr/libexec/applekeystored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cf1c` | `0x9d6c4` | **`+0x7a8`** |
| `__DATA.__bss` | `0xbea0` | `0xbf20` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x21f6` | `0x2266` | **`+0x70`** |
| `__TEXT.__cstring` | `0xfddc` | `0xfe3c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2350` | `0x2388` | **`+0x38`** |
| `__DATA.__data` | `0x72a8` | `0x72d8` | **`+0x30`** |
| `__TEXT.__const` | `0x9d09` | `0x9d39` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x1398` | `0x13a8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x20e0` | `0x20f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1078` | `0x1080` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x4850` | `0x4848` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x5f4` | `0x5f8` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x2f0` | `0x2f4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2369.0.0.0.7
+2383.0.6.0.1

-  Functions: 3294
-  Symbols:   914
-  CStrings:  2629
+  Functions: 3300
+  Symbols:   915
+  CStrings:  2636
Symbols:
+ _swift_release_x10
CStrings:
+ "com.apple.acx_test_runner"
+ "com.apple.cameraispd"
+ "com.apple.usernotificationsd"
+ "com.apple.xctspawn"
+ "completed janitor task"
+ "completed sweep successfully, violations=%ld repairs=%ld errors=%ld"
+ "completed sweep with errors, violations=%ld repairs=%ld errors=%ld"
+ "janitor task expiration requested"
+ "rescheduling janitor task"
+ "starting janitor task"
+ "sweep error: %@"
- "aborted sweep, violations=%ld repairs=%ld errors=%ld"
- "completed sweep, violations=%ld repairs=%ld errors=%ld"
- "starting janitor background task"
- "sweep failed: %@"
```
