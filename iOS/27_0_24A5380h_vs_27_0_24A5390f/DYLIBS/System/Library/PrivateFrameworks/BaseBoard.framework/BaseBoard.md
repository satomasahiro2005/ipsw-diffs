## BaseBoard

> `/System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1788` | `0xa1be8` | **`+0x460`** |
| `__AUTH_CONST.__objc_const` | `0xd530` | `0xd6c8` | **`+0x198`** |
| `__TEXT.__gcc_except_tab` | `0x10f88` | `0x1105c` | **`+0xd4`** |
| `__AUTH.__objc_data` | `0x12c0` | `0x1360` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x70b4` | `0x713c` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x8cc0` | `0x8d20` | **`+0x60`** |
| `__TEXT.__cstring` | `0x8f53` | `0x8f0e` | **`-0x45`** |
| `__DATA_CONST.__objc_selrefs` | `0x3200` | `0x3240` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x52b0` | `0x52e8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x858` | `0x868` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA.__bss` | `0x50` | `0x48` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x864` | `0x86c` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x4b8` | `0x4c0` | **`+0x8`** |

### Other Changes

```diff

-825.0.0.0.0
+827.0.0.0.0

-  Functions: 3030
-  Symbols:   5938
-  CStrings:  1591
+  Functions: 3039
+  Symbols:   5964
+  CStrings:  1594
Symbols:
+ +[BSActionInactivation createWithCallStack:reason:]
+ +[BSActionUsageViolation createWithMessage:priorInactivation:]
+ -[BSAction abortForUsageViolation:]
+ -[BSActionInactivation .cxx_destruct]
+ -[BSActionInactivation callStack]
+ -[BSActionInactivation reason]
+ -[BSActionUsageViolation .cxx_destruct]
+ -[BSActionUsageViolation abort]
+ -[_BSActionResponder _handleUsageViolation:priorInactivation:action:]
+ _OBJC_CLASS_$_BSActionInactivation
+ _OBJC_CLASS_$_BSActionUsageViolation
+ _OBJC_IVAR_$_BSActionInactivation._callStack
+ _OBJC_IVAR_$_BSActionInactivation._reason
+ _OBJC_IVAR_$_BSActionUsageViolation._message
+ _OBJC_IVAR_$_BSActionUsageViolation._priorInactivation
+ _OBJC_IVAR_$__BSActionResponder._lock_inactivation
+ _OBJC_METACLASS_$_BSActionInactivation
+ _OBJC_METACLASS_$_BSActionUsageViolation
+ __OBJC_$_CLASS_METHODS_BSActionInactivation
+ __OBJC_$_CLASS_METHODS_BSActionUsageViolation
+ __OBJC_$_INSTANCE_METHODS_BSActionInactivation
+ __OBJC_$_INSTANCE_METHODS_BSActionUsageViolation
+ __OBJC_$_INSTANCE_VARIABLES_BSActionInactivation
+ __OBJC_$_INSTANCE_VARIABLES_BSActionUsageViolation
+ __OBJC_$_PROP_LIST_BSActionInactivation
+ __OBJC_CLASS_RO_$_BSActionInactivation
+ __OBJC_CLASS_RO_$_BSActionUsageViolation
+ __OBJC_METACLASS_RO_$_BSActionInactivation
+ __OBJC_METACLASS_RO_$_BSActionUsageViolation
- _OBJC_IVAR_$__BSActionResponder._lock_action_encoded
- _OBJC_IVAR_$__BSActionResponder._lock_action_sent
- _OBJC_IVAR_$__BSActionResponder._lock_inactivationCallStack
CStrings:
+ "%@\nprevious inactivation was at %@"
+ "%@ : action=%@"
+ "BSActionUsageViolation.m"
+ "cannot -encode from an inactive instance"
+ "cannot -sendResponse: from an inactive instance"
+ "cannot -sendResponse: if no response was expected"
+ "cannot -setNullificationHandler: on an inactive instance"
- "cannot -encode from an inactive instance : action=%@\nprevious inactivation was at %@"
- "cannot -sendResponse: from an inactive instance : action=%@\nprevious inactivation was at %@"
- "cannot -sendResponse: if no response was expected : action=%@"
- "cannot -setNullificationHandler: on an inactive instance : action=%@\nprevious inactivation was at %@"
```
