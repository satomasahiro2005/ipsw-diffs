## JetAsset

> `/System/Library/PrivateFrameworks/JetAsset.framework/JetAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56f3c` | `0x58514` | **`+0x15d8`** |
| `__TEXT.__cstring` | `0x18c5` | `0x19e5` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x2a88` | `0x2990` | **`-0xf8`** |
| `__TEXT.__const` | `0x8e28` | `0x8de8` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0xab0` | `0xae8` | **`+0x38`** |
| `__DATA.__data` | `0xec0` | `0xee8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1910` | `0x1928` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1a22` | `0x1a3a` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x28c` | `0x278` | **`-0x14`** |
| `__AUTH_CONST.__const` | `0x44d8` | `0x44e8` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1708` | `0x1718` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xb0` | `0xa0` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x78` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1ae0` | `0x1ad0` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x70` | `0x64` | **`-0xc`** |
| `__AUTH.__data` | `0x920` | `0x928` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-10.0.47.0.0
+10.1.8.0.0

-  Functions: 2381
-  Symbols:   958
-  CStrings:  153
+  Functions: 2388
+  Symbols:   962
+  CStrings:  159
Symbols:
+ ___swift_closure_destructor.31Tm
+ _objc_retain_x23
+ _objc_retain_x24
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic _____y_____G 9JetEngine14DaemonResponseO AA0c2NoD0V
- ___swift_closure_destructor.37Tm
CStrings:
+ "DaemonSession.sendSync"
+ "Error occurred when sending synchronous request to daemon: "
+ "Received an XPC error sending synchronous request: "
+ "Sending synchronous prewarm request to daemon"
+ "Sending synchronous request to daemon: "
+ "XPC session (sendSync) cancelled: "
+ "sendSync complete"
- "Sending one-way prewarm request to daemon"
```
