## IPConfiguration

> `/System/Library/SystemConfiguration/IPConfiguration.bundle/IPConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c984` | `0x5cad8` | **`+0x154`** |
| `__TEXT.__auth_stubs` | `0x1070` | `0x10d0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x61a9` | `0x61dc` | **`+0x33`** |
| `__DATA_CONST.__auth_got` | `0x838` | `0x868` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4226` | `0x424b` | **`+0x25`** |
| `__DATA_CONST.__cfstring` | `0x2b20` | `0x2b40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1dc8` | `0x1db0` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x3b8` | `0x3b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc40` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__TEXT.__const`

### Other Changes

```diff

-551.0.0.0.0
+553.0.0.0.0

-  Functions: 1031
-  Symbols:   489
-  CStrings:  1737
+  Functions: 1030
+  Symbols:   494
+  CStrings:  1740
Symbols:
+ _dispatch_mach_connect
+ _dispatch_mach_create_f
+ _dispatch_mach_mig_demux
+ _dispatch_mach_msg_get_msg
+ _dispatch_set_qos_class_fallback
+ _mach_msg_destroy
+ _mach_port_deallocate
- __dispatch_source_type_mach_recv
- _dispatch_mig_server
CStrings:
+ "%s: dispatch_mach_mig_demux failed"
+ "IPConfigurationAgent"
+ "dispatch_mach_create() failed"
+ "ipconfiguration_mach_handler"
+ "no domains "
- "%s: failed %d"
- "server_init_block_invoke"
```
