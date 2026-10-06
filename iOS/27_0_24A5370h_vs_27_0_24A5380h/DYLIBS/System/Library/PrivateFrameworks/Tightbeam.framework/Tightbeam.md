## Tightbeam

> `/System/Library/PrivateFrameworks/Tightbeam.framework/Tightbeam`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1738` | `0x1978` | **`+0x240`** |
| `__AUTH.__data` | `0x220` | `—` | **`-0x220`** |
| `__TEXT.__text` | `0x3f5c0` | `0x3f478` | **`-0x148`** |
| `__TEXT.__cstring` | `0x54ab` | `0x55ab` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0xe6e` | `0xe4a` | **`-0x24`** |
| `__AUTH_CONST.__objc_const` | `0x1848` | `0x1868` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x18e8` | `0x1900` | **`+0x18`** |
| `__TEXT.__const` | `0x2438` | `0x2428` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1438` | `0x1444` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xaf8` | `0xb00` | **`+0x8`** |
| `__DATA.__data` | `0x418` | `0x410` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1120` | `0x1118` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-631.0.0.0.2
+631.0.3.0.0

-  Functions: 2072
-  Symbols:   1281
-  CStrings:  411
+  Functions: 2064
+  Symbols:   1278
+  CStrings:  419
Symbols:
+ _symbolic _____ 9Tightbeam12FirstContactO13HandlerResultV
- _get_type_metadata 9Tightbeam0A7MessageV noncopyable
- _get_type_metadata 9Tightbeam15TransportBufferVSg noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____ 9Tightbeam12FirstContactO0bC13HandlerResultV
CStrings:
+ "Allocation failed"
+ "Deferred send unsupported"
+ "Invalid configuration"
+ "Message encode failed"
+ "No notification pending"
+ "Notification check-in failed"
+ "Notification receive failed"
+ "Validation failed"
+ "rawServiceConnection: message is not backed by a service connection"
- "serviceConnection: message is not backed by a service connection"
```
