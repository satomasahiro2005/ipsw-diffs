## STSXPCHelper

> `/System/Library/PrivateFrameworks/STSXPCHelperClient.framework/XPCServices/STSXPCHelper.xpc/STSXPCHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a654` | `0x3a880` | **`+0x22c`** |
| `__TEXT.__ustring` | `0x268` | `0x34c` | **`+0xe4`** |
| `__TEXT.__cstring` | `0x95b7` | `0x9626` | **`+0x6f`** |
| `__DATA_CONST.__cfstring` | `0x5d00` | `0x5d60` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x7c4` | `0x7bc` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6.0.15.0.0
+6.1.3.0.0

-  CStrings:  2533
+  CStrings:  2536
Functions:
~ sub_100018070 : 1116 -> 1572
~ sub_10001f014 -> sub_10001f1dc : 884 -> 876
~ sub_1000351ac -> sub_10003536c : 848 -> 924
~ sub_1000354fc -> sub_100035708 : 772 -> 796
~ sub_100035810 -> sub_100035a34 : 204 -> 212
CStrings:
+ "LE: writeData %s (completion observed at stall check)"
+ "LE: writeData hit %.0fs backstop while still draining; pendingBytes=%lu — failing write"
+ "LE: writeData progressing, remaining=%lu (elapsed %.1fs)"
+ "LE: writeData stalled — no progress for %.1fs (elapsed %.1fs); pendingBytes=%lu — failing write"
- "LE: writeData timed out after %.1fs; pendingBytes=%lu — failing write"
```
