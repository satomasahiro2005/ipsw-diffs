## Accounts

> `/System/Library/Frameworks/Accounts.framework/Accounts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59198` | `0x590ec` | **`-0xac`** |
| `__AUTH_CONST.__auth_got` | `0x658` | `0x660` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x22b8` | `0x22b0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x417c` | `0x4174` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1ab8` | **`-0x8`** |

### Other Changes

```diff

-1119.0.0.0.0
+1122.0.0.0.0

-  Functions: 1948
+  Functions: 1947
Symbols:
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ _dispatch_suspend
- -[ACTimedExpirer _unsafeCancelTimer]
- ___block_descriptor_48_e8_32bs40w_e5_v8?0lw40l8s32l8
Functions:
~ ___37-[ACTimedExpirer scheduleExpiration:]_block_invoke : 360 -> 324
~ ___29-[ACTimedExpirer cancelTimer]_block_invoke : 8 -> 32
~ ___37-[ACTimedExpirer scheduleExpiration:]_block_invoke_2 : 96 -> 16
- -[ACTimedExpirer _unsafeCancelTimer]
```
