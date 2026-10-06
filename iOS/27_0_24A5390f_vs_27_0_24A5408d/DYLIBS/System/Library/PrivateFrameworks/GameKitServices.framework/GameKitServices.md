## GameKitServices

> `/System/Library/PrivateFrameworks/GameKitServices.framework/GameKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7714c` | `0x77df0` | **`+0xca4`** |
| `__TEXT.__oslogstring` | `0x1190c` | `0x11c00` | **`+0x2f4`** |
| `__AUTH_CONST.__objc_const` | `0x4d70` | `0x4ec0` | **`+0x150`** |
| `__TEXT.__gcc_except_tab` | `0x81c` | `0x774` | **`-0xa8`** |
| `__TEXT.__objc_methlist` | `0x2ed8` | `0x2f70` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf8` | `0x1c50` | **`+0x58`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__cstring` | `0x6a7d` | `0x6aaf` | **`+0x32`** |
| `__TEXT.__unwind_info` | `0xfc8` | `0xff8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xa58` | `0xa30` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x190` | `0x1b0` | **`+0x20`** |
| `__DATA.__bss` | `0xb0` | `0xc0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4f4` | `0x504` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x9b8` | `0x9c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |

### Other Changes

```diff

-2235.57.1.0.0
+2235.63.1.1.0

-  Functions: 1614
-  Symbols:   2439
-  CStrings:  1891
+  Functions: 1634
+  Symbols:   2465
+  CStrings:  1901
Symbols:
+ +[GKVoiceChatDictionary expectedActualDictionaryKeyTypes]
+ +[GKVoiceChatDictionary isValidActualDictionary:]
+ -[GKDiscoveryBonjour _cancelAllTxtLookups]
+ -[GKDiscoveryBonjour _trackTxtLookupContext:]
+ -[GKDiscoveryBonjour _untrackTxtLookupContext:]
+ -[GKDiscoveryBonjourTxtContext callback]
+ -[GKDiscoveryBonjourTxtContext dealloc]
+ -[GKDiscoveryBonjourTxtContext owner]
+ -[GKDiscoveryBonjourTxtContext serviceRef]
+ -[GKDiscoveryBonjourTxtContext setCallback:]
+ -[GKDiscoveryBonjourTxtContext setOwner:]
+ -[GKDiscoveryBonjourTxtContext setServiceRef:]
+ _OBJC_CLASS_$_GKDiscoveryBonjourTxtContext
+ _OBJC_IVAR_$_GKDiscoveryBonjour._txtLookupContexts
+ _OBJC_IVAR_$_GKDiscoveryBonjourTxtContext._callback
+ _OBJC_IVAR_$_GKDiscoveryBonjourTxtContext._owner
+ _OBJC_IVAR_$_GKDiscoveryBonjourTxtContext._serviceRef
+ _OBJC_METACLASS_$_GKDiscoveryBonjourTxtContext
+ __OBJC_$_INSTANCE_METHODS_GKDiscoveryBonjourTxtContext
+ __OBJC_$_INSTANCE_VARIABLES_GKDiscoveryBonjourTxtContext
+ __OBJC_$_PROP_LIST_GKDiscoveryBonjourTxtContext
+ __OBJC_CLASS_RO_$_GKDiscoveryBonjourTxtContext
+ __OBJC_METACLASS_RO_$_GKDiscoveryBonjourTxtContext
+ ___57+[GKVoiceChatDictionary expectedActualDictionaryKeyTypes]_block_invoke
+ ___block_descriptor_57_e8_32o40o_e22_v16?0"NSDictionary"8ls32l8s40l8
+ _expectedActualDictionaryKeyTypes.expectedKeyTypes
+ _expectedActualDictionaryKeyTypes.once
+ _objc_setProperty_atomic_copy
- ___block_descriptor_48_e8_32o40r_e5_v8?0lr40l8s32l8
- ___block_descriptor_57_e8_32o40r_e22_v16?0"NSDictionary"8lr40l8s32l8
CStrings:
+ " [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/GameKitServices.subproj/Sources/Gecko/GCKSession.c:%d: packet iLen=%d exceeds dest capacity=%d; dropping"
+ " [%s] %s:%d Failed to mutableCopy decoded actualDictionary"
+ " [%s] %s:%d GKVoiceChatDictionary decoded actualDictionary failed key/value validation"
+ " [%s] %s:%d GKVoiceChatDictionary decoded actualDictionary is not an NSDictionary"
+ " [%s] %s:%d GKVoiceChatDictionary key is not an NSString"
+ " [%s] %s:%d GKVoiceChatDictionary unknown key %s"
+ " [%s] %s:%d GKVoiceChatDictionary value for key %s has unexpected type"
+ " [%s] %s:%d parseConnectedPeers got non-array plist"
+ " [%s] %s:%d parseConnectedPeers got oversize array count=%lu max=%d"
+ "+[GKVoiceChatDictionary isValidActualDictionary:]"
+ "10:49:15"
+ "Aug  4 2026"
- "04:38:29"
- "Jul 11 2026"
```
