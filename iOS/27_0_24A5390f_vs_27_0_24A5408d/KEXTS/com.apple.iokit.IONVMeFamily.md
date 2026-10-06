## com.apple.iokit.IONVMeFamily

> `com.apple.iokit.IONVMeFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x5c5dc` | `0x5c61c` | **`+0x40`** |
| `__TEXT_EXEC.__auth_stubs` | `0xdf0` | `0xe00` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6f8` | `0x700` | **`+0x8`** |

### Other Changes

```diff

-877.0.6.0.0
-  Functions: 3588
+877.0.7.0.0
+  Functions: 3589
Functions:
+ sub_fffffff00a1c155c
~ __ZN16IONVMeController8PolledIOEhP18IOMemoryDescriptorjyy18IOPolledCompletionjPKhm : 2004 -> 2000
```
