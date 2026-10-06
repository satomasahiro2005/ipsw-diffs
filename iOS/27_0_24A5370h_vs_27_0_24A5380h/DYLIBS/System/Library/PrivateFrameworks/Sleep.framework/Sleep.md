## Sleep

> `/System/Library/PrivateFrameworks/Sleep.framework/Sleep`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x930` | `0x598` | **`-0x398`** |
| `__DATA_DIRTY.__objc_data` | `0x15e0` | `0x1978` | **`+0x398`** |
| `__DATA_DIRTY.__data` | `—` | `0xf8` | **`+0xf8`** |
| `__AUTH.__data` | `0x1e8` | `0x110` | **`-0xd8`** |
| `__TEXT.__text` | `0x5b6b8` | `0x5b600` | **`-0xb8`** |
| `__DATA.__data` | `0x16e0` | `0x16b0` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x5a0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4c29` | `0x4c09` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__DATA.__common` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x159` | `0x161` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 2892
-  Symbols:   5093
-  CStrings:  1123
+  Functions: 2891
+  Symbols:   5092
+  CStrings:  1122
Symbols:
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 5Sleep0C29FocusConfigurationInputSignalC5State33_248D772D7535224398991984147DA603LLV
- _get_type_metadata 15Synchronization5MutexVy5Sleep0C29FocusConfigurationInputSignalC5State33_248D772D7535224398991984147DA603LLVG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
- "com.apple.HealthKit"
```
