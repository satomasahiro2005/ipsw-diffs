## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.restore.im4p/exclave_pmm_exclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c440` | `0x4ce98` | **`+0xa58`** |
| `__DATA.__const` | `0x1348` | `0x1498` | **`+0x150`** |
| `__TEXT.__cstring` | `0x11c84` | `0x11d83` | **`+0xff`** |

### Same-size Content Changes

- `__DATA.__auth_ptr`
- `__DATA.__data`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-1460.0.0.502.2
-  Functions: 1203
+1485.0.0.0.3
+  Functions: 1212

-  CStrings:  1501
+  CStrings:  1510
CStrings:
+ "B16@?0^v8"
+ "B16@?0^{tb_message_accumulator_s=QQQ*}8"
+ "Unexpected return from endpoint!"
+ "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from vas zeroer %p\n"
+ "^v8@?0"
+ "tb_list.c"
+ "thread holds resources after return from call"
+ "v20@?0^{tb_connection_s=(?=[97c]^v)}8I16"
+ "v24@?0^{tb_list_node_s=^{tb_list_node_s}Q^v@?}8^B16"
+ "vascore__zeroer_zero_attrs_leave_mapped"
- "[VAS abort in function %s at line %d] [true: (%s)] Unable to unmap frame %#lx from table %#lx at addr %#lx for zeroing\n"
```
