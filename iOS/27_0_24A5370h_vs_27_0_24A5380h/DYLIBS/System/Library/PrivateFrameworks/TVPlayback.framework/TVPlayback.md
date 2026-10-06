## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x682e0` | `0x68498` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x6d43` | `0x6d96` | **`+0x53`** |
| `__AUTH.__objc_data` | `0x8c0` | `0x870` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xaf0` | `0xb40` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x8b8` | `0x8d8` | **`+0x20`** |
| `__DATA.__bss` | `0xb0` | `0xa8` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x228` | `0x230` | **`+0x8`** |

### Other Changes

```diff

-634.0.0.0.0
+635.0.1.0.0

-  Functions: 2268
+  Functions: 2272

-  CStrings:  1435
+  CStrings:  1438
Symbols:
+ _NSCocoaErrorDomain
- ___44-[TVPDownload _registerStateMachineHandlers]_block_invoke_5
CStrings:
+ "Treating NSUserCancelledError as cancellation"
+ "rtcAgentUserInfo: %@"
+ "sessionInfo: %@"
```
