## ApplePushService

> `/System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fb74` | `0x1ff20` | **`+0x3ac`** |
| `__AUTH_CONST.__cfstring` | `0x1fe0` | `0x20e0` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1edb` | `0x1f6b` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x268f` | `0x26e9` | **`+0x5a`** |
| `__TEXT.__unwind_info` | `0x8a0` | `0x8c8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x2a70` | `0x2a90` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x172c` | `0x174c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xed0` | `0xee8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xec8` | `0xed0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x13c` | `0x140` | **`+0x4`** |

### Other Changes

```diff

-1157.100.1.0.0
+1161.100.1.0.0

-  Functions: 853
-  Symbols:   1524
-  CStrings:  573
+  Functions: 858
+  Symbols:   1531
+  CStrings:  584
Symbols:
+ -[APSConnection _addPriorityBoostTopicsToXPCMessage:]
+ -[APSConnection _onIvarQueue_setPriorityBoostsForTopics:]
+ -[APSConnection setPriorityBoostsForTopics:]
+ GCC_except_table215
+ GCC_except_table228
+ GCC_except_table231
+ GCC_except_table300
+ _APSPriorityBoostEntitlement
+ _APSStringForQOSClass
+ _OBJC_IVAR_$_APSConnection._priorityBoostTopics
+ ___44-[APSConnection setPriorityBoostsForTopics:]_block_invoke
- GCC_except_table214
- GCC_except_table227
- GCC_except_table230
- GCC_except_table299
CStrings:
+ "%@ _connection is NULL in _setPriorityBoostsForTopics"
+ "%@: Setting PriorityBoostTopics: %@"
+ "BACKGROUND"
+ "DEFAULT"
+ "UNKNOWN(%u)"
+ "UNSPECIFIED"
+ "USER_INITIATED"
+ "USER_INTERACTIVE"
+ "UTILITY"
+ "com.apple.private.aps-priority-boost"
+ "priorityBoostTopics"
```
