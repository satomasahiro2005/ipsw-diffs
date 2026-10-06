## AccessibilityPlatformTranslation

> `/System/Library/PrivateFrameworks/AccessibilityPlatformTranslation.framework/AccessibilityPlatformTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15a0c` | `0x16ac4` | **`+0x10b8`** |
| `__AUTH_CONST.__objc_const` | `0x1430` | `0x17c0` | **`+0x390`** |
| `__TEXT.__objc_methlist` | `0x11dc` | `0x1354` | **`+0x178`** |
| `__DATA_CONST.__objc_selrefs` | `0xe70` | `0xf18` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x280` | `0x320` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x6ab` | `0x726` | **`+0x7b`** |
| `__DATA.__objc_ivar` | `0x108` | `0x140` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x510` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x380` | `0x390` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__cstring` | `0x26ae` | `0x26b1` | **`+0x3`** |

### Other Changes

```diff

-591.4.2.0.0
+591.4.4.0.0

-  Functions: 429
-  Symbols:   933
-  CStrings:  406
+  Functions: 458
+  Symbols:   992
+  CStrings:  408
Symbols:
+ -[AXPRemoteCacheManager _runtimeDelegateToken]
+ -[AXPRemoteCacheManager dealloc]
+ -[AXPRemoteCacheManager set_runtimeDelegateToken:]
+ -[AXPRuntimeDelegateRegistration .cxx_destruct]
+ -[AXPRuntimeDelegateRegistration cachedTreeClientType]
+ -[AXPRuntimeDelegateRegistration delegate]
+ -[AXPRuntimeDelegateRegistration requestResolvingBehavior]
+ -[AXPRuntimeDelegateRegistration setCachedTreeClientType:]
+ -[AXPRuntimeDelegateRegistration setDelegate:]
+ -[AXPRuntimeDelegateRegistration setRequestResolvingBehavior:]
+ -[AXPTokenDelegateRegistration .cxx_destruct]
+ -[AXPTokenDelegateRegistration cachedTreeClientType]
+ -[AXPTokenDelegateRegistration delegate]
+ -[AXPTokenDelegateRegistration requestResolvingBehavior]
+ -[AXPTokenDelegateRegistration setCachedTreeClientType:]
+ -[AXPTokenDelegateRegistration setDelegate:]
+ -[AXPTokenDelegateRegistration setRequestResolvingBehavior:]
+ -[AXPTranslator bridgeDelegateTokenToRegistrationLookup]
+ -[AXPTranslator broadcastNotification:data:associatedObject:]
+ -[AXPTranslator hasRegisteredRuntimeDelegates]
+ -[AXPTranslator registerBridgeTokenDelegate:requestResolvingBehavior:cachedTreeClientType:forToken:]
+ -[AXPTranslator registerRuntimeDelegate:requestResolvingBehavior:cachedTreeClientType:forToken:]
+ -[AXPTranslator requestResolvingBehaviorForBridgeDelegateToken:]
+ -[AXPTranslator runtimeDelegateTokenToRegistrationLookup]
+ -[AXPTranslator setBridgeDelegateTokenToRegistrationLookup:]
+ -[AXPTranslator setRuntimeDelegateTokenToRegistrationLookup:]
+ -[AXPTranslator tokenDelegateForBridgeDelegateToken:]
+ -[AXPTranslator unregisterBridgeDelegateForToken:]
+ -[AXPTranslator unregisterRuntimeDelegateForToken:]
+ GCC_except_table225
+ GCC_except_table235
+ GCC_except_table243
+ GCC_except_table347
+ _OBJC_CLASS_$_AXPRuntimeDelegateRegistration
+ _OBJC_CLASS_$_AXPTokenDelegateRegistration
+ _OBJC_IVAR_$_AXPRemoteCacheManager.__runtimeDelegateToken
+ _OBJC_IVAR_$_AXPRuntimeDelegateRegistration._cachedTreeClientType
+ _OBJC_IVAR_$_AXPRuntimeDelegateRegistration._delegate
+ _OBJC_IVAR_$_AXPRuntimeDelegateRegistration._requestResolvingBehavior
+ _OBJC_IVAR_$_AXPTokenDelegateRegistration._cachedTreeClientType
+ _OBJC_IVAR_$_AXPTokenDelegateRegistration._delegate
+ _OBJC_IVAR_$_AXPTokenDelegateRegistration._requestResolvingBehavior
+ _OBJC_IVAR_$_AXPTranslator._authoritativeBridgeDelegateToken
+ _OBJC_IVAR_$_AXPTranslator._authoritativeRuntimeDelegateToken
+ _OBJC_IVAR_$_AXPTranslator._bridgeDelegateAuthorityGeneration
+ _OBJC_IVAR_$_AXPTranslator._bridgeDelegateTokenToRegistrationLookup
+ _OBJC_IVAR_$_AXPTranslator._registrationLookupLock
+ _OBJC_IVAR_$_AXPTranslator._runtimeDelegateAuthorityGeneration
+ _OBJC_IVAR_$_AXPTranslator._runtimeDelegateTokenToRegistrationLookup
+ _OBJC_METACLASS_$_AXPRuntimeDelegateRegistration
+ _OBJC_METACLASS_$_AXPTokenDelegateRegistration
+ __OBJC_$_INSTANCE_METHODS_AXPRuntimeDelegateRegistration
+ __OBJC_$_INSTANCE_METHODS_AXPTokenDelegateRegistration
+ __OBJC_$_INSTANCE_VARIABLES_AXPRuntimeDelegateRegistration
+ __OBJC_$_INSTANCE_VARIABLES_AXPTokenDelegateRegistration
+ __OBJC_$_PROP_LIST_AXPRuntimeDelegateRegistration
+ __OBJC_$_PROP_LIST_AXPTokenDelegateRegistration
+ __OBJC_CLASS_RO_$_AXPRuntimeDelegateRegistration
+ __OBJC_CLASS_RO_$_AXPTokenDelegateRegistration
+ __OBJC_METACLASS_RO_$_AXPRuntimeDelegateRegistration
+ __OBJC_METACLASS_RO_$_AXPTokenDelegateRegistration
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- GCC_except_table223
- GCC_except_table227
- GCC_except_table240
- GCC_except_table318
CStrings:
+ "Bridge delegate for token %@ is registered but has been deallocated!"
+ "No delegate available to service request for token %@"
+ "r\""
- "\"\""
```
