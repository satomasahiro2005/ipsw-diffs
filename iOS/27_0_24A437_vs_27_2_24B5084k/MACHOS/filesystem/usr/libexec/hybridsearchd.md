## hybridsearchd

> `/usr/libexec/hybridsearchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3870` | `0x3e2c` | **`+0x5bc`** |
| `__TEXT.__eh_frame` | `0x240` | `0x2c0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2d8` | `0x350` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0xec` | `0x120` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0x81` | `0xb1` | **`+0x30`** |
| `__TEXT.__const` | `0x152` | `0x17a` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1c0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x760` | `0x780` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb0` | `0x98` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xa6` | `0xb6` | **`+0x10`** |
| `__DATA.__data` | `0x78` | `0x70` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1c` | `0x20` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x18` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-67.0.0.0.0
+73.2.0.0.0

-  Functions: 106
-  Symbols:   73
-  CStrings:  10
+  Functions: 115
+  Symbols:   78
+  CStrings:  11
Symbols:
+ __swift_stdlib_bridgeErrorToNSError
+ _swift_errorRetain
+ _swift_release_x27
+ _swift_retain_x27
+ _swift_task_immediate
+ _swift_task_isCurrentExecutorWithFlags
- _objc_release_x23
CStrings:
+ "XPCDistributed server failed: %@"
```
