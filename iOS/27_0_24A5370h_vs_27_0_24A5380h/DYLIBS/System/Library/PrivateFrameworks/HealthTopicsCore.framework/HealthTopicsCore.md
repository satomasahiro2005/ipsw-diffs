## HealthTopicsCore

> `/System/Library/PrivateFrameworks/HealthTopicsCore.framework/HealthTopicsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19260` | `0x19010` | **`-0x250`** |
| `__DATA.__data` | `0x5f0` | `0x580` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0x578` | `0x5c8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x948` | `0x972` | **`+0x2a`** |
| `__TEXT.__cstring` | `0x157` | `0x137` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x968` | `0x950` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x6e8` | `0x6f0` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 868
-  Symbols:   418
-  CStrings:  16
+  Functions: 861
+  Symbols:   417
+  CStrings:  15
Symbols:
+ _symbolic _____yScCyx______pGSgG 15Synchronization5MutexVAARi_zrlE s5ErrorP
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 16HealthTopicsCore13TopicRegistryC5State33_305C039A775A821DD794ED632617F3F9LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 16HealthTopicsCore14MockTopicStoreC5State33_51845E7EA95FC205D62DA8EE0A43E3D4LLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 16HealthTopicsCore15RequestRegistryC5State33_AFEA4D51E5EACA7F4C71290F92D24121LLV
- _get_type_metadata 15Synchronization5MutexVy16HealthTopicsCore13TopicRegistryC5State33_305C039A775A821DD794ED632617F3F9LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy16HealthTopicsCore14MockTopicStoreC5State33_51845E7EA95FC205D62DA8EE0A43E3D4LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy16HealthTopicsCore15RequestRegistryC5State33_AFEA4D51E5EACA7F4C71290F92D24121LLVG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVyScCyxs5Error_pGSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
- "com.apple.HealthKit"
```
