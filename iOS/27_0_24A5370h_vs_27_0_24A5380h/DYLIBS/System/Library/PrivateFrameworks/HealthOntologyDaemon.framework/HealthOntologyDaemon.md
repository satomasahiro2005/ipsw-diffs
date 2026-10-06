## HealthOntologyDaemon

> `/System/Library/PrivateFrameworks/HealthOntologyDaemon.framework/HealthOntologyDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d32c` | `0x2d5f8` | **`+0x2cc`** |
| `__DATA_CONST.__const` | `0x1978` | `0x19f0` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xc30` | `0xc80` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x628` | `0x668` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x2220` | `0x2240` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x3f20` | `0x3f40` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1d5a` | `0x1d7a` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe68` | `0xe88` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x4a0` | `0x4b8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3f8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1e8` | `0x1ec` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 1093
-  Symbols:   2137
+  Functions: 1098
+  Symbols:   2146
Symbols:
+ GCC_except_table68
+ GCC_except_table81
+ _OBJC_IVAR_$_HDOntologyUpdateCoordinator._bgstCompletionQueue
+ ___117-[HDOntologyUpdateCoordinator _runOntologyUpdateWithShouldDefer:addExpirationHandler:reason:activityName:completion:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_56_e8_32s40bs48r_e20_v24?0q8"NSError"16ls32l8r48l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
+ _dispatch_async
+ _objc_sync_enter
+ _objc_sync_exit
- GCC_except_table79
CStrings:
+ "%{public}@: Expiration handler fired, cancelling in-flight ontology update work and acking BGST as deferred"
+ "bgst-completion"
- "%{public}@: Expiration handler fired, cancelling in-flight ontology update work"
- "\xa1"
```
