## libsystem_kernel.dylib

> `/usr/lib/system/libsystem_kernel.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34ee0` | `0x34f00` | **`+0x20`** |
| `__TEXT.__const` | `0xc80` | `0xc90` | **`+0x10`** |

### Other Changes

```diff

-13432.0.5.502.4
-  Functions: 1554
-  Symbols:   1724
+13432.0.50.502.2
+  Functions: 1555
+  Symbols:   1725
Symbols:
+ _exclaves_device_state
Functions:
~ _mach_msg_destroy : 328 -> 324
~ ___sfi_ctl : 52 -> 56
~ __libkernel_strlen : 264 -> 256
~ __libkernel_memset : 140 -> 128
+ _exclaves_device_state
~ __mach_vsnprintf : 392 -> 404
~ _inet_rule_iterate : 176 -> 184
~ _eth_rule_iterate : 176 -> 184
~ _host_get_boot_info : 536 -> 528
~ _host_kernel_version : 520 -> 512
~ __kernelrpc_mach_port_kobject_description : 576 -> 568
~ _netname_version : 420 -> 416
```
