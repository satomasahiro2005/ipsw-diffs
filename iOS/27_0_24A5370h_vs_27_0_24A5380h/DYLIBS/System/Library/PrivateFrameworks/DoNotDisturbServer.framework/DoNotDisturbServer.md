## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc20b8` | `0xc2248` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x26768` | `0x268c8` | **`+0x160`** |
| `__DATA_DIRTY.__objc_data` | `0x35b8` | `0x36f0` | **`+0x138`** |
| `__AUTH.__objc_data` | `0x9c0` | `0x8d8` | **`-0xe8`** |
| `__DATA_DIRTY.__data` | `0xb0` | `0x190` | **`+0xe0`** |
| `__AUTH.__data` | `0xe8` | `0x28` | **`-0xc0`** |
| `__TEXT.__objc_methlist` | `0xaa8c` | `0xab0c` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x4dc0` | `0x4e00` | **`+0x40`** |
| `__TEXT.__const` | `0x6d8` | `0x718` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x118d0` | `0x11900` | **`+0x30`** |
| `__DATA.__data` | `0x3360` | `0x3340` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xed0` | `0xee8` | **`+0x18`** |
| `__DATA.__bss` | `0x200` | `0x1f0` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x218` | `0x228` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa5c` | `0xa68` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x618` | `0x620` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x3e8` | `0x3f0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a28` | `0x2a30` | **`+0x8`** |

### Other Changes

```diff

-502.0.100.0.0
+506.0.0.0.0

-  Functions: 3923
-  Symbols:   7213
-  CStrings:  2289
+  Functions: 3933
+  Symbols:   7235
+  CStrings:  2290
Symbols:
+ +[DNDSSleepModeEvent eventWithBiomeEventBody:]
+ -[DNDSSleepModeEvent .cxx_destruct]
+ -[DNDSSleepModeEvent assertionReason]
+ -[DNDSSleepModeEvent expectedEndDate]
+ -[DNDSSleepModeEvent initWithState:reason:expectedEndDate:]
+ -[DNDSSleepModeEvent isActive]
+ -[DNDSSleepModeEvent reasonDescription]
+ -[DNDSSleepModeEvent shouldIgnore]
+ -[DNDSSleepModeEvent stateDescription]
+ -[DNDSSleepingTriggerManager _refreshWithMode:sleepEvent:]
+ _OBJC_CLASS_$_BMSleepModeEvent
+ _OBJC_CLASS_$_BMUserFocusSleepMode
+ _OBJC_CLASS_$_DNDSSleepModeEvent
+ _OBJC_IVAR_$_DNDSSleepModeEvent._expectedEndDate
+ _OBJC_IVAR_$_DNDSSleepModeEvent._reason
+ _OBJC_IVAR_$_DNDSSleepModeEvent._state
+ _OBJC_METACLASS_$_DNDSSleepModeEvent
+ __OBJC_$_CLASS_METHODS_DNDSSleepModeEvent
+ __OBJC_$_INSTANCE_METHODS_DNDSSleepModeEvent
+ __OBJC_$_INSTANCE_VARIABLES_DNDSSleepModeEvent
+ __OBJC_$_PROP_LIST_DNDSSleepModeEvent
+ __OBJC_CLASS_RO_$_DNDSSleepModeEvent
+ __OBJC_METACLASS_RO_$_DNDSSleepModeEvent
+ ___58-[DNDSSleepingTriggerManager _refreshWithMode:sleepEvent:]_block_invoke
+ ___58-[DNDSSleepingTriggerManager _refreshWithMode:sleepEvent:]_block_invoke_2
- -[DNDSSleepingTriggerManager _refreshWithMode:event:]
- ___53-[DNDSSleepingTriggerManager _refreshWithMode:event:]_block_invoke
- ___53-[DNDSSleepingTriggerManager _refreshWithMode:event:]_block_invoke_2
CStrings:
+ "Unexpected sleeping event body class: %{public}@"
```
