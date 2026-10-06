## IntelligencePlatformCore

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/IntelligencePlatformCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb41648` | `0xb3e69c` | **`-0x2fac`** |
| `__TEXT.__oslogstring` | `0x1fc43` | `0x1fd6b` | **`+0x128`** |
| `__DATA.__bss` | `0x86250` | `0x86260` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x2da20` | `0x2da10` | **`-0x10`** |
| `__TEXT.__const` | `0x7d590` | `0x7d5a0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x19c` | `0x1ac` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2654f` | `0x2655f` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4610` | `0x4618` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e48` | `0x2e50` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x60080` | `0x60088` | **`+0x8`** |

### Other Changes

```diff

-190.0.0.0.0
+193.0.0.0.0

-  Functions: 67694
-  Symbols:   1004
-  CStrings:  5831
+  Functions: 67614
+  Symbols:   1005
+  CStrings:  5834
Symbols:
+ _XPC_ACTIVITY_INTERVAL_5_MIN
CStrings:
+ "GDBiomeStreamStoreErasure: latestDeleteBookmarkForStream: tombstone bookmark for %@ can no longer be resumed, reading from the start of the substore instead. Error: %@"
+ "ViewUpdate: %s: current bookmark is no longer valid: %@"
+ "ViewUpdate: %s: deletion bookmark is no longer valid: %@"
```
