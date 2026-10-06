## AdCore

> `/System/Library/PrivateFrameworks/AdCore.framework/AdCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3073c` | `0x30a98` | **`+0x35c`** |
| `__TEXT.__cstring` | `0x3f41` | `0x3fed` | **`+0xac`** |
| `__AUTH_CONST.__objc_const` | `0x5c10` | `0x5c70` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x4cc0` | `0x4d00` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x380` | `0x3a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x6a8` | `0x6c8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ff8` | `0x2018` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4054` | `0x4074` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xc30` | `0xc48` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4b0` | `0x4c4` | **`+0x14`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3ec` | `0x3f8` | **`+0xc`** |

### Other Changes

```diff

-638.1.5.0.0
+638.1.7.0.0

-  Functions: 1413
-  Symbols:   2366
-  CStrings:  653
+  Functions: 1419
+  Symbols:   2378
+  CStrings:  655
Symbols:
+ -[ADCoreSettings dealloc]
+ -[ADCoreSettings invalidateAccountCache]
+ -[ADCoreSettings setIdentifierForAdvertisingAllowedCoalescedAsync:]
+ GCC_except_table14
+ GCC_except_table36
+ GCC_except_table40
+ _OBJC_IVAR_$_ADCoreSettings._accountCacheLock
+ _OBJC_IVAR_$_ADCoreSettings._cachedIsManagedAppleID
+ _OBJC_IVAR_$_ADCoreSettings._isManagedAppleIDCacheValid
+ ___67-[ADCoreSettings setIdentifierForAdvertisingAllowedCoalescedAsync:]_block_invoke
+ ___67-[ADCoreSettings setIdentifierForAdvertisingAllowedCoalescedAsync:]_block_invoke_2
+ ___block_descriptor_33_e5_v8?0l
+ _setIdentifierForAdvertisingAllowedCoalescedAsync:.identifierForAdvertisingQueue
+ _setIdentifierForAdvertisingAllowedCoalescedAsync:.onceToken
- GCC_except_table34
- GCC_except_table38
CStrings:
+ "Invalidated cached managed-Apple-ID after account change."
+ "com.apple.adcore.setIdentifierForAdvertisingAllowed"
+ "com.apple.adplatforms.UserAccountChangeCompletedNotification"
- "%F"
```
