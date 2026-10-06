## RunningBoard

> `/System/Library/PrivateFrameworks/RunningBoard.framework/RunningBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ad9c` | `0x7b184` | **`+0x3e8`** |
| `__AUTH_CONST.__objc_const` | `0xdb70` | `0xdbb0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xb84` | `0xbac` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f40` | `0x2f50` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x63fc` | `0x640c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa60` | `0xa68` | **`+0x8`** |
| `__TEXT.__cstring` | `0x7d45` | `0x7d46` | **`+0x1`** |

### Other Changes

```diff

-1084.40.3.0.1
+1084.40.6.0.0

-  Functions: 2825
-  Symbols:   4891
+  Functions: 2826
+  Symbols:   4895
Symbols:
+ -[RBProcessMonitorObserver _lock_shouldSendState:forHandle:]
+ GCC_except_table27
+ GCC_except_table31
+ _OBJC_IVAR_$_RBProcessMonitorObserver._hasVisibilityOnlyConfig
+ _OBJC_IVAR_$_RBProcessMonitorObserver._lastVisibleByIdentity
- GCC_except_table26
Functions:
~ ___66-[RBProcessMonitorObserver processMonitor:didChangeProcessStates:]_block_invoke : 824 -> 984
~ -[RBProcessMonitorObserver _lock_addConfigurationStatesToPending:] : 708 -> 828
~ -[RBProcessMonitorObserver _lock_rebuildConfiguration] : 496 -> 544
~ -[RBProcessMonitorObserver initWithMonitor:forProcess:connection:] : 416 -> 440
~ -[RBProcessMonitorObserver .cxx_destruct] : 160 -> 172
~ -[RBProcessMonitorObserver invalidate] : 124 -> 132
+ -[RBProcessMonitorObserver _lock_shouldSendState:forHandle:]
```
