## libAONConnection.dylib

> `/usr/lib/libAONConnection.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7e8` | `0xab6c` | **`+0x384`** |
| `__DATA_CONST.__const` | `0x300` | `0x328` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1f1d` | `0x1f3d` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xd38` | `0xd55` | **`+0x1d`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x238` | `0x240` | **`+0x8`** |

### Other Changes

```diff

-236.0.0.0.1
+251.0.0.0.0

-  Functions: 201
-  Symbols:   361
-  CStrings:  223
+  Functions: 206
+  Symbols:   366
+  CStrings:  225
Symbols:
+ GCC_except_table146
+ __ZN4ULPN15TBClientAdaptor11reportEventEj18aon_net_flow_event
+ ____ZN4ULPN15TBClientAdaptor11reportEventEj18aon_net_flow_event_block_invoke
+ _aon_ip_config_get_service_class
+ _aon_ip_config_set_service_class
+ _aonnetworking_tlshandshakeconfig__sizeof
- GCC_except_table142
CStrings:
+ "%s: invalid service class %u"
+ "aon_ip_config_set_service_class"
```
