## sysstatuscheck

> `/usr/libexec/sysstatuscheck`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd100` | `0xd0cc` | **`-0x34`** |
| `__TEXT.__gcc_except_tab` | `0x5a4` | `0x5a0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-233.0.0.0.0
+233.0.0.502.1
Functions:
~ sub_100001fd0 : 1012 -> 1044
~ sub_1000042fc -> sub_10000431c : 484 -> 472
~ sub_100009f58 -> sub_100009f6c : 532 -> 508
~ sub_10000a16c -> sub_10000a168 : 176 -> 152
~ sub_10000a21c -> sub_10000a200 : 228 -> 204
```
