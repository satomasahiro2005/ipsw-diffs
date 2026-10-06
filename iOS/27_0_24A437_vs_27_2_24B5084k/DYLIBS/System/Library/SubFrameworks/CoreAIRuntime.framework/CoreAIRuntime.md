## CoreAIRuntime

> `/System/Library/SubFrameworks/CoreAIRuntime.framework/CoreAIRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53d368` | `0x53f718` | **`+0x23b0`** |
| `__AUTH_CONST.__objc_const` | `0x5390` | `0x5560` | **`+0x1d0`** |
| `__AUTH.__data` | `0xd80` | `0xed0` | **`+0x150`** |
| `__AUTH_CONST.__const` | `0xa208` | `0xa348` | **`+0x140`** |
| `__TEXT.__cstring` | `0xc021` | `0xc0f1` | **`+0xd0`** |
| `__TEXT.__const` | `0xdfd0` | `0xe070` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x3570` | `0x35e8` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x1154` | `0x11c4` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x31b5` | `0x321d` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x3900` | `0x395c` | **`+0x5c`** |
| `__TEXT.__swift5_reflstr` | `0x258d` | `0x25dd` | **`+0x50`** |
| `__DATA.__data` | `0x1e10` | `0x1e50` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1508` | `0x1540` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x12370` | `0x12338` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x5d90` | `0x5db8` | **`+0x28`** |
| `__DATA.__common` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1a50` | `0x1a58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3ec` | `0x3f4` | **`+0x8`** |

### Other Changes

```diff

-3600.83.2.11.1
+3605.5.4.0.0

-  Functions: 7694
-  Symbols:   336
-  CStrings:  1018
+  Functions: 7729
+  Symbols:   339
+  CStrings:  1023
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _notify_cancel
+ _notify_register_dispatch
CStrings:
+ " out of range 0..<"
+ "Inference Model Discover"
+ "attribute index "
+ "com.apple.coreai.instruments-recording-epoch-registration"
+ "com.apple.instruments.record-started"
```
