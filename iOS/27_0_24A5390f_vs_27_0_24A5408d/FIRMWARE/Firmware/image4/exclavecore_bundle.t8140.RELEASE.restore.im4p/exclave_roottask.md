## exclave_roottask

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_roottask`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ea854` | `0x4e9638` | **`-0x121c`** |
| `__DATA.__bss` | `0x1b818` | `0x1ada8` | **`-0xa70`** |
| `__TEXT.__eh_frame` | `0x21d6c` | `0x21e74` | **`+0x108`** |
| `__TEXT.__swift5_assocty` | `0x7158` | `0x7208` | **`+0xb0`** |
| `__TEXT.__const` | `0xf2330` | `0xf23c0` | **`+0x90`** |
| `__DATA.__const` | `0x353c8` | `0x35438` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0xcf4c` | `0xcfbc` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x163e0` | `0x16410` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xb27c` | `0xb2ac` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x2e14` | `0x2e3c` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x125e0` | `0x12604` | **`+0x24`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__data`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__TEXT.__chain_fixups`
- `__TEXT.__cstring`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1490.0.20.0.0
-  Functions: 19267
+1490.0.21.0.0
+  Functions: 19271

-  CStrings:  6081
+  CStrings:  6084
CStrings:
+ "Can't skip by a negative offset"
+ "Escaping Closure Propagated"
+ "Swift/BorrowingSequence.swift"
```
