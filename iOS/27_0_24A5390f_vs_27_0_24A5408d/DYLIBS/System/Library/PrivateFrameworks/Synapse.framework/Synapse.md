## Synapse

> `/System/Library/PrivateFrameworks/Synapse.framework/Synapse`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37a5c` | `0x37944` | **`-0x118`** |
| `__AUTH_CONST.__objc_const` | `0xdbb8` | `0xdb00` | **`-0xb8`** |
| `__DATA.__data` | `0xb40` | `0xae0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x2f89` | `0x2f3d` | **`-0x4c`** |
| `__AUTH_CONST.__const` | `0x440` | `0x400` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x325c` | `0x322c` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x4459` | `0x4431` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2480` | `0x24a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x14f8` | `0x14d8` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb4c` | `0xb38` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x1278` | `0x1268` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xf0` | `0xe8` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x48` | `0x40` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cb8` | `0x1cb0` | **`-0x8`** |

### Other Changes

```diff

-148.0.0.0.0
+149.0.0.0.0

-  Functions: 1491
-  Symbols:   2545
-  CStrings:  740
+  Functions: 1487
+  Symbols:   2534
+  CStrings:  739
Symbols:
+ -[SYBacklinkMonitorOperation backlinkFilterCache]
+ -[SYBacklinkMonitorOperation setBacklinkFilterCache:]
+ -[SYBacklinkMonitorService _filterCachesByActivityType]
+ -[SYBacklinkMonitorService set_filterCachesByActivityType:]
+ _OBJC_IVAR_$_SYBacklinkMonitorOperation._backlinkFilterCache
+ _OBJC_IVAR_$_SYBacklinkMonitorService.__filterCachesByActivityType
+ _SYPathByRemovingPrivatePrefix
- -[SYBacklinkMonitorClient _filterCache]
- -[SYBacklinkMonitorClient _previousFilterCacheMatched]
- -[SYBacklinkMonitorClient set_filterCache:]
- -[SYBacklinkMonitorClient set_previousFilterCacheMatched:]
- -[SYBacklinkMonitorClient updateWithFilterCache:]
- -[SYBacklinkMonitorServiceHandle setFilterCache:]
- _OBJC_IVAR_$_SYBacklinkMonitorClient.__filterCache
- _OBJC_IVAR_$_SYBacklinkMonitorClient.__previousFilterCacheMatched
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SYBacklinkMonitorClientProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_SYBacklinkMonitorClientProtocol
- __OBJC_$_PROTOCOL_REFS_SYBacklinkMonitorClientProtocol
- __OBJC_CLASS_PROTOCOLS_$_SYBacklinkMonitorClient
- __OBJC_LABEL_PROTOCOL_$_SYBacklinkMonitorClientProtocol
- __OBJC_PROTOCOL_$_SYBacklinkMonitorClientProtocol
- __OBJC_PROTOCOL_REFERENCE_$_SYBacklinkMonitorClientProtocol
- ___49-[SYBacklinkMonitorServiceHandle setFilterCache:]_block_invoke
- ___54-[SYBacklinkMonitorService _notesActivationDidChange:]_block_invoke
- ___block_descriptor_32_e57_v32?0"NSNumber"8"SYBacklinkMonitorServiceHandle"16^B24l
CStrings:
+ "/private"
+ "/private/var/"
+ "BacklinkOperation %p: Filter cache miss, skipping query and hiding indicator."
+ "\xa1"
- "/var/mobile/Library/Mail/AttachmentData/"
- "BacklinkClient: Changed activity was filtered out: %p."
- "BacklinkServiceHandle: Error creating remote service proxy: %@"
- "v32@?0@\"NSNumber\"8@\"SYBacklinkMonitorServiceHandle\"16^B24"
- "\x91"
```
