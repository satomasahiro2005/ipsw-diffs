## finhealthd

> `/System/Library/PrivateFrameworks/FinHealth.framework/finhealthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe358` | `0xead8` | **`+0x780`** |
| `__TEXT.__eh_frame` | `0xe50` | `0xf68` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x520` | `0x570` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x558` | `0x592` | **`+0x3a`** |
| `__TEXT.__oslogstring` | `0x5b8` | `0x5e8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x758` | `0x780` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0xb8` | `0xe0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xad0` | `0xaf0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1bc` | `0x1dc` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x258` | `0x26c` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x570` | `0x580` | **`+0x10`** |
| `__TEXT.__const` | `0x3f2` | `0x402` | **`+0x10`** |
| `__DATA.__objc_const` | `0x468` | `0x470` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1ac` | `0x1b4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x6c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0x78` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1.9.1.22.0
+1.9.1.24.0

-  Functions: 440
-  Symbols:   276
-  CStrings:  125
+  Functions: 461
+  Symbols:   278
+  CStrings:  128
Symbols:
+ _$s13FinHealthCore17GroupingSyncGuardC5resetyyFTj
+ _$s13FinHealthCore21UpcomingPaymentsCacheC5resetyyFTj
+ _swift_retain_x1
- _swift_retain_x24
CStrings:
+ "resetAll:"
+ "resetAll: resetting upcoming payments state"
+ "v24@0:8@?<v@?>16"
```
