## CoreSpeechExclave

> `/System/Library/PrivateFrameworks/CoreSpeechExclave.framework/CoreSpeechExclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x206a8` | `0x22600` | **`+0x1f58`** |
| `__DATA_DIRTY.__data` | `—` | `0x2d0` | **`+0x2d0`** |
| `__AUTH.__data` | `0x2c8` | `—` | **`-0x2c8`** |
| `__TEXT.__oslogstring` | `0xc5c` | `0xdcc` | **`+0x170`** |
| `__AUTH_CONST.__auth_got` | `0x658` | `0x6b8` | **`+0x60`** |
| `__TEXT.__cstring` | `0xc35` | `0xbd5` | **`-0x60`** |
| `__TEXT.__eh_frame` | `0x1ab0` | `0x1af0` | **`+0x40`** |
| `__AUTH.__objc_data` | `0x70` | `0x48` | **`-0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x78` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xa98` | `0xab8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x88a` | `0x89c` | **`+0x12`** |
| `__TEXT.__const` | `0x1fb0` | `0x1fc0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x9d9` | `0x9e9` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xabc` | `0xac8` | **`+0xc`** |
| `__DATA.__data` | `0x228` | `0x230` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xe0` | `0xe8` | **`+0x8`** |

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  Functions: 774
-  Symbols:   426
-  CStrings:  164
+  Functions: 784
+  Symbols:   436
+  CStrings:  172
Symbols:
+ __swiftEmptySetSingleton
+ _bzero
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _symbolic ShySSG
+ _symbolic _____ySSG s11_SetStorageC
CStrings:
+ "Failed to disable AOE for %s: %@"
+ "Failed to enable AOE for %s: %@"
+ "Forwarding disable(from:%s) to connection"
+ "Forwarding enable(from:%s) to connection"
+ "Replay enable(from:%s) failed: %@"
+ "com.apple.corespeech."
+ "disable(from:%s) without matching enable"
+ "enable(from:%s) called while already enabled"
+ "enable(from:%s) deferred — not connected"
- "AlwaysOnExclaveClient: Attempted to keep always on exclaved alive before connecting to the always on exclaved daemon."
```
