## TelemetryDiskChecker

> `/System/Library/PrivateFrameworks/iCloudDriveService.framework/XPCServices/TelemetryDiskChecker.xpc/TelemetryDiskChecker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xa7a` | `0xa9e` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x1400` | `0x1420` | **`+0x20`** |
| `__TEXT.__cstring` | `0x100b` | `0x1023` | **`+0x18`** |
| `__TEXT.__text` | `0x6a60` | `0x6a78` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x17cd` | `0x17de` | **`+0x11`** |
| `__DATA.__objc_selrefs` | `0x640` | `0x648` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0

-  Functions: 111
+  Functions: 107

-  CStrings:  421
+  CStrings:  422
CStrings:
+ "SELECT COUNT(*), MAX(rowid) FROM client_items WHERE item_localsyncupstate != 0 AND NOT item_id_is_documents(item_id) %@"
+ "SELECT COUNT(*), MAX(rowid) FROM client_unapplied_table WHERE throttle_state IN (1) %@"
+ "[DEBUG] we have %lld active apply jobs (e.g. rowid:%lld)%@"
+ "[DEBUG] we have %lld active sync jobs (e.g. rowid:%lld)%@"
+ "longLongAtIndex:"
- "SELECT COUNT(*) FROM client_items WHERE item_localsyncupstate != 0 AND NOT item_id_is_documents(item_id) %@"
- "SELECT COUNT(*) FROM client_unapplied_table WHERE throttle_state IN (1) %@"
- "[DEBUG] we have %lld active apply jobs%@"
- "[DEBUG] we have %lld active sync jobs%@"
```
