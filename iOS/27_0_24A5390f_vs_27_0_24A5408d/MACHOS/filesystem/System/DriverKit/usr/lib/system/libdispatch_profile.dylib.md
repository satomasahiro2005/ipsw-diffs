## libdispatch_profile.dylib

> `/System/DriverKit/usr/lib/system/libdispatch_profile.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x496cc` | `0x496dc` | **`+0x10`** |
| `__TEXT.__dof_voucher` | `0x2d6a` | `0x2d71` | **`+0x7`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1605.0.1.0.0
+1605.0.2.0.0

-  Functions: 1366
+  Functions: 1367
Functions:
~ __dispatch_block_sync_invoke : 512 -> 372
~ _OUTLINED_FUNCTION_42 : 12 -> 20
~ _OUTLINED_FUNCTION_43 : 20 -> 12
+ _dispatch_block_sync_invoke.cold.3
```
