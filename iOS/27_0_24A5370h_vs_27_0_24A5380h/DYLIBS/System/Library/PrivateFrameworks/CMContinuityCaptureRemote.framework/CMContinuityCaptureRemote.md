## CMContinuityCaptureRemote

> `/System/Library/PrivateFrameworks/CMContinuityCaptureRemote.framework/CMContinuityCaptureRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1d40` | `0x1c00` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x140` | **`+0x140`** |
| `__TEXT.__text` | `0xaf9c8` | `0xafa64` | **`+0x9c`** |
| `__DATA.__bss` | `0xca0` | `0xc60` | **`-0x40`** |
| `__DATA_DIRTY.__bss` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x24c0` | `0x2488` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0xb8fc` | `0xb8cd` | **`-0x2f`** |
| `__AUTH_CONST.__objc_const` | `0xac70` | `0xac50` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2ab8` | `0x2ad0` | **`+0x18`** |
| `__DATA.__data` | `0x15c0` | `0x15b0` | **`-0x10`** |
| `__TEXT.__const` | `0x13e0` | `0x13d0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x5f94` | `0x5fa4` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2ed0` | `0x2ed8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x838` | `0x834` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x1c0` | `0x1c4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-753.0.0.122.3
+758.0.0.122.2

-  Functions: 3181
+  Functions: 3185
Symbols:
+ -[CMContinuityCaptureRemoteSessionManager _performActivationOfSession:forDevice:deviceModel:]
+ ___93-[CMContinuityCaptureRemoteSessionManager _performActivationOfSession:forDevice:deviceModel:]_block_invoke
- _OBJC_IVAR_$_CMContinuityCaptureNWServer._identifier
- ___82-[CMContinuityCaptureRemoteSessionManager _activateSession:forDevice:deviceModel:]_block_invoke
CStrings:
+ "User has opted out of Continuity Capture"
- "User has opted out of Continuity Capture but proceeding to populate device capabilities"
```
