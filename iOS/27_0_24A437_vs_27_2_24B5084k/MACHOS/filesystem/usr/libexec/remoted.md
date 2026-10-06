## remoted

> `/usr/libexec/remoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d5f4` | `0x3d6f8` | **`+0x104`** |
| `__TEXT.__oslogstring` | `0x8502` | `0x85d2` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x1120` | `0x1098` | **`-0x88`** |
| `__TEXT.__objc_stubs` | `0x24a0` | `0x2520` | **`+0x80`** |
| `__TEXT.__cstring` | `0x21d9` | `0x2243` | **`+0x6a`** |
| `__DATA_CONST.__cfstring` | `0xea0` | `0xf00` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x254c` | `0x259a` | **`+0x4e`** |
| `__DATA.__objc_const` | `0x2810` | `0x2850` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1560` | `0x1590` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x12c8` | `0x12b0` | **`-0x18`** |
| `__DATA.__bss` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x21c` | `0x220` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-245.0.7.0.0
+245.40.8.0.0

-  Functions: 1376
+  Functions: 1385

-  CStrings:  1776
+  CStrings:  1786
Symbols:
+ _MGGetBoolAnswer
- _IORegistryEntryFromPath
CStrings:
+ "%{public}@> Device connection interrupted expectedly because of %{public}s; reattaching"
+ "%{public}@> Peer UUID changed across reconnect; reattaching so clients re-discover it"
+ "NLWYUp5icK9sRsPDI7XJtw"
+ "Not using public NCM interface due to the existence of private NCM interface"
+ "Not using public NCM interface on compute node"
+ "RvCUAjrf7O/zAzV1StnBlg"
+ "Using public NCM interface"
+ "XjG5q4m+sX+F9Prap4MBAQ"
+ "_needs_reattach"
+ "a reattach"
+ "a reset"
+ "beingReset"
+ "both controller and node device according to MobileGestalt"
+ "compute controller backend not initialized, cannot add device on %{public}s"
+ "connect_loopback_with_override"
+ "disconnect_loopback"
+ "needsReattach"
+ "override"
+ "reattach"
+ "shouldReattachForHandshake:"
- "%{public}@> Device connection interrupted. Proceed to reset"
- "IODeviceTree:/"
- "IODeviceTree:/%s"
- "IORegistryEntryCreateIterator: %d"
- "IORegistryEntryGetName: %d"
- "assertion failure: \"name\" -> %llu"
- "both manta-b and manta-c device found in device tree"
- "failed to find ioreg path: %{public}s"
- "manta-b"
- "manta-c"
```
