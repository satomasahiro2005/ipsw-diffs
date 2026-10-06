## libffi.dylib

> `/usr/lib/libffi.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd32c` | `0xd38c` | **`+0x60`** |

### Other Changes

```text
Functions:
~ _ffi_raw_to_ptrarray : 96 -> 100
~ _ffi_ptrarray_to_raw : 316 -> 320
~ _ffi_prep_cif_var : 172 -> 176
~ _ffi_get_struct_offsets : 13632 -> 13620
~ _ffi_closure_alloc : 560 -> 564
~ _ffi_prep_cif_machdep : 300 -> 308
~ _is_vfp_type : 312 -> 320
~ _ffi_call_int : 1304 -> 1348
~ _ffi_closure_SYSV_inner : 952 -> 988
~ _is_hfa0 : 100 -> 92
~ _initialize_aggregate : 244 -> 248
```
