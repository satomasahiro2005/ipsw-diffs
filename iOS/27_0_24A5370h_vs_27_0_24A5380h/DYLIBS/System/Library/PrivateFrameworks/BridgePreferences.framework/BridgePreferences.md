## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38bc0` | `0x39130` | **`+0x570`** |
| `__TEXT.__cstring` | `0x4692` | `0x4712` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x43c` | `0x4a4` | **`+0x68`** |
| `__TEXT.__dlopen_cstrs` | `0x336` | `0x390` | **`+0x5a`** |
| `__DATA_CONST.__const` | `0xe90` | `0xed0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x29e8` | `0x2a18` | **`+0x30`** |
| `__DATA.__bss` | `0x4d8` | `0x4e8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa48` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7a8` | `0x7b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdd0` | `0xdd8` | **`+0x8`** |

### Other Changes

```diff

-1355.0.0.1.0
+1359.0.0.0.0

-  Functions: 1409
-  Symbols:   2539
-  CStrings:  843
+  Functions: 1412
+  Symbols:   2548
+  CStrings:  846
Symbols:
+ _OBJC_CLASS_$_CTXPCServiceSubscriptionContext
+ _SetupAssistantLibraryCore.frameworkLibrary
+ ___67-[BPSWatchMigrationController shouldBeDisplayedGivenMigrationData:]_block_invoke_2
+ ___SetupAssistantLibraryCore_block_invoke
+ ___block_descriptor_48_e8_32s40r_e40_v24?0"CTRemoteDeviceList"8"NSError"16lr40l8s32l8
+ ___getBYSetupAssistantHasCompletedInitialRunSymbolLoc_block_invoke
+ _audit_stringSetupAssistant
+ _dispatch_group_wait
+ _getBYSetupAssistantHasCompletedInitialRunSymbolLoc.ptr
CStrings:
+ "BPSWatchMigrationController - RemotePairedDeviceInfo Error for slot: %@"
+ "BYSetupAssistantHasCompletedInitialRun"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant"
+ "v24@?0@\"CTRemoteDeviceList\"8@\"NSError\"16"
- "Localizable-N230"
```
