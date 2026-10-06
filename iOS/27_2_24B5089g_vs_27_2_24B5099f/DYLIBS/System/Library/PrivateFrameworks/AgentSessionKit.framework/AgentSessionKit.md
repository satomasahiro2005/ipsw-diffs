## AgentSessionKit

> `/System/Library/PrivateFrameworks/AgentSessionKit.framework/AgentSessionKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fd90` | `0x92a50` | **`+0x2cc0`** |
| `__TEXT.__eh_frame` | `0x6110` | `0x63f0` | **`+0x2e0`** |
| `__TEXT.__unwind_info` | `0x3ae8` | `0x3b98` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x1675` | `0x16f5` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x2d20` | `0x2d68` | **`+0x48`** |
| `__TEXT.__const` | `0xbf1c` | `0xbf5c` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1f5a` | `0x1f1a` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x2704` | `0x2742` | **`+0x3e`** |
| `__TEXT.__swift_as_ret` | `0x240` | `0x27c` | **`+0x3c`** |
| `__AUTH_CONST.__const` | `0x8378` | `0x83a8` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xb30` | `0xb50` | **`+0x20`** |
| `__DATA.__data` | `0x1128` | `0x1148` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x4c8` | `0x4e4` | **`+0x1c`** |
| `__TEXT.__swift5_capture` | `0xafc` | `0xb14` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x2548` | `0x2558` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1fc` | `0x204` | **`+0x8`** |

### Other Changes

```diff

-297.8.0.2.0
+297.12.0.1.2

-  Functions: 6109
-  Symbols:   189
-  CStrings:  278
+  Functions: 6169
+  Symbols:   191
+  CStrings:  279
Symbols:
+ _objc_retain_x27
+ _swift_retain_x9
+ _swift_task_future_wait_throwing
- _objc_retain_x26
CStrings:
+ "Remote Configuration:"
+ "remoteConfiguration"
+ "remoteConfigurationDefaults"
- "AgentSessionKit/AgentSessionStoreXPCService.swift"
- "AgentSessionStoreXPCClient: BidirectionalXPCServiceClientConnection.init failed: "
```
