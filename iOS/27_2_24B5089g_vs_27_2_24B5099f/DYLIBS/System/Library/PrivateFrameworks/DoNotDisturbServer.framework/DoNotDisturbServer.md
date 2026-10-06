## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4c54` | `0xc4d4c` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x11d6f` | `0x11ddf` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x978` | `0x928` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x36f8` | `0x3748` | **`+0x50`** |
| `__DATA.__data` | `0x33c8` | `0x33a8` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x190` | `0x1b0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2a80` | `0x2a88` | **`+0x8`** |

### Other Changes

```diff

-511.2.3.0.0
+511.2.6.0.0

-  Functions: 3984
+  Functions: 3985

-  CStrings:  2308
+  CStrings:  2309
Functions:
~ ___73-[DNDSAppFocusConfigurationCoordinator assertion:didInvalidateWithError:]_block_invoke : 200 -> 332
+ ___73-[DNDSAppFocusConfigurationCoordinator assertion:didInvalidateWithError:]_block_invoke.cold.2
CStrings:
+ "App Protection auth assertion invalidated for a subject with no bundle identifier; ignoring. subject=%{public}@"
```
