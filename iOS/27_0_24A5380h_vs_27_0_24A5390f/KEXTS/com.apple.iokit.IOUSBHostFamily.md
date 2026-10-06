## com.apple.iokit.IOUSBHostFamily

> `com.apple.iokit.IOUSBHostFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xa379` | `0xa25c` | **`-0x11d`** |
| `__TEXT.__os_log` | `0x866a` | `0x85bf` | **`-0xab`** |
| `__TEXT_EXEC.__text` | `0x942b4` | `0x94240` | **`-0x74`** |

### Other Changes

```diff

-1617.0.3.0.0
+1617.0.9.0.0

-  CStrings:  1150
+  CStrings:  1147
Functions:
~ sub_fffffff00a5d0cfc -> sub_fffffff00a5f73bc : 100 -> 148
~ sub_fffffff00a5d2d90 -> sub_fffffff00a5f9480 : 252 -> 272
~ sub_fffffff00a6351ec -> sub_fffffff00a65b8f0 : 2540 -> 2356
CStrings:
+ "smc-port-number"
+ "usb-c-port-number"
- "%s@%s: %s::%s: Client %p is requesting %umA wake and %umA sleep for port %u\n"
- "%s@%s: %s::%s: Client %p port %u has EDT current overrides of %umA wake and %umA sleep\n"
- "%s@%s: %s::%s: Granting %umA wake and %umA sleep based on override for port %u\n"
- "%s@%s: %s::%s: Port %u %umA/%umA wake and %umA/%umA sleep\n"
- "UsbCPortNumber"
```
