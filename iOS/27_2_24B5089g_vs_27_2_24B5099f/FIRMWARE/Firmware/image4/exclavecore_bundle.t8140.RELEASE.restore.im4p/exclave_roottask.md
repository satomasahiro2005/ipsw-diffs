## exclave_roottask

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_roottask`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4eccdc` | `0x4eced0` | **`+0x1f4`** |
| `__TEXT.__eh_frame` | `0x221fc` | `0x2226c` | **`+0x70`** |
| `__TEXT.__cstring` | `0x3d90c` | `0x3d93c` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1490.40.25.0.0
-  Functions: 19329
+1490.40.28.0.0
+  Functions: 19336

-  CStrings:  6110
+  CStrings:  6111
CStrings:
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
