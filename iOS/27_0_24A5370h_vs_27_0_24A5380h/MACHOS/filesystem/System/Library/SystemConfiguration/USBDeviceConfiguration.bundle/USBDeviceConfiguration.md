## USBDeviceConfiguration

> `/System/Library/SystemConfiguration/USBDeviceConfiguration.bundle/USBDeviceConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x256` | `0x278` | **`+0x22`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x340` | `0x320` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x1a0` | `0x190` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__text` | `0xc04` | `0xbfc` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-896.0.0.0.0
+896.0.3.0.0

-  Symbols:   70
-  CStrings:  17
+  Symbols:   67
+  CStrings:  18
Symbols:
- _IOMIGMachPortGetPort
- _mach_port_mod_refs
- _mach_task_self_
Functions:
~ _start : 516 -> 552
~ sub_c34 -> sub_c58 : 416 -> 372
CStrings:
+ "DevUSB: pthread_create failed: %d"
```
