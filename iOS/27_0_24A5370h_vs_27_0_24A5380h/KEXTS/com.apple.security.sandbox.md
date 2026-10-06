## com.apple.security.sandbox

> `com.apple.security.sandbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1eab69` | `0x1ed021` | **`+0x24b8`** |
| `__TEXT_EXEC.__text` | `0x38f4c` | `0x38ee0` | **`-0x6c`** |

### Other Changes

```diff

-3051.0.18.0.3
+3051.0.30.0.0
Functions:
~ sub_fffffff00a871a60 -> sub_fffffff00a872a00 : 452 -> 444
~ ___hook_iokit_check_set_properties_block_invoke : 1580 -> 1560
~ _hook_policy_init : 5600 -> 5584
~ sub_fffffff00a887d7c -> sub_fffffff00a888cf0 : 224 -> 212
~ sub_fffffff00a887f8c -> sub_fffffff00a888ef4 : 432 -> 420
~ _syscall_reference_retain : 876 -> 872
~ sub_fffffff00a8884a8 -> sub_fffffff00a889400 : 480 -> 468
~ _populate_event_context : 4488 -> 4500
~ _hook_cred_label_update_execve : 5392 -> 5372
~ sub_fffffff00a896f0c -> sub_fffffff00a897e50 : 1056 -> 1048
~ sub_fffffff00a89f6e4 -> sub_fffffff00a8a0620 : 748 -> 752
~ _syscall_check_sandbox : 4092 -> 4080
```
