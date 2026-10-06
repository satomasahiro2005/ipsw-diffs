## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291f20` | `0x291f78` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x5ff0` | `0x5ff8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-1582.4.0.0.0
+1582.5.0.0.0

-  Functions: 14196
-  Symbols:   12068
+  Functions: 14198
+  Symbols:   12070
Symbols:
+ __ZN24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
+ __ZThn96_N24AppleBCMWLANNANInterface15flushFlowQueuesEP10ether_addr
CStrings:
+ "\"AppleBCMWLANV3_driverkit-1582.5\""
+ "AppleBCMWLANV3_driverkit-1582.5"
+ "Sep 14 2026 21:06:04"
- "\"AppleBCMWLANV3_driverkit-1582.4\""
- "AppleBCMWLANV3_driverkit-1582.4"
- "Sep  4 2026 20:21:50"
```
