## uarpd

> `/usr/libexec/uarpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6600` | `0xa6b6c` | **`+0x56c`** |
| `__TEXT.__objc_methname` | `0xf9fa` | `0xfad0` | **`+0xd6`** |
| `__TEXT.__objc_stubs` | `0xac40` | `0xad00` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x987e` | `0x98fd` | **`+0x7f`** |
| `__TEXT.__cstring` | `0xb685` | `0xb6ee` | **`+0x69`** |
| `__DATA_CONST.__cfstring` | `0x56c0` | `0x5700` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x89c0` | `0x8a00` | **`+0x40`** |
| `__DATA.__objc_const` | `0x10a18` | `0x10a48` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x3340` | `0x3370` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2470` | `0x2480` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xb84` | `0xb88` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-1587.40.28.0.0
+1587.40.33.0.0

-  Functions: 4025
+  Functions: 4030

-  CStrings:  5101
+  CStrings:  5114
CStrings:
+ "%s: %@ has no LastDateConnected; pruning legacy entry"
+ "%s: database entry %@ not updated for greater active version of %@"
+ "%s: database entry %@ not updated for greater available version of %@"
+ "-[UARPPruner isEndpointDatabaseEntryURLRipeForPruning:baseTime:]"
+ "LastDateConnected"
+ "LastDateDisconnected"
+ "T@\"NSDate\",&,V_lastDateConnected"
+ "T@\"NSDate\",&,V_lastDateDisconnected"
+ "_lastDateConnected"
+ "_lastDateDisconnected"
+ "date"
+ "isEndpointDatabaseEntryURLRipeForPruning:baseTime:"
+ "isURLRipeForPruning:baseTime:"
+ "lastDateConnected"
+ "lastDateDisconnected"
+ "setLastDateConnected:"
+ "setLastDateDisconnected:"
- "%s: Do not offer asset %@ to %@; reported no firmware available"
- "TB,R,V_blockFirmwareUpdate"
- "_blockFirmwareUpdate"
- "blockFirmwareUpdate"
```
