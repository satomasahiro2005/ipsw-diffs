## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x277d68` | `0x278034` | **`+0x2cc`** |
| `__TEXT.__oslogstring` | `0x1ee8a` | `0x1efaa` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x19f8` | `0x1a48` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x3e3c8` | `0x3e3e8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6d60` | `0x6d78` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4cb4` | `0x4cc0` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x7028` | `0x7030` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x6218` | `0x6220` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x109c` | `0x10a0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-355.2.6.200.0
+355.2.10.100.0

-  Functions: 10971
-  Symbols:   11136
-  CStrings:  4022
+  Functions: 10974
+  Symbols:   11137
+  CStrings:  4026
Symbols:
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._monitorLock
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._monitorLock_applicationRootNode
+ _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._monitorLock_applicationStateMonitor
- _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._lock_applicationRootNode
- _OBJC_IVAR_$_PBFPosterExtensionDataStoreXPCServiceGlue._lock_applicationStateMonitor
CStrings:
+ "_lock_teardownDataStore: applicationRootNode cancel raised: %{public}@"
+ "_lock_teardownDataStore: applicationStateMonitor invalidate raised: %{public}@"
+ "_lock_teardownDataStore: dataStore invalidate raised: %{public}@"
+ "_lock_teardownDataStore: runtimeAssertionManager invalidate raised: %{public}@"
```
