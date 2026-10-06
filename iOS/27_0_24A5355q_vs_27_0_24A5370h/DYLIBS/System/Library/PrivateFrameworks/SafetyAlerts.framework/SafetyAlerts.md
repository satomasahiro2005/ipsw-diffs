## SafetyAlerts

> `/System/Library/PrivateFrameworks/SafetyAlerts.framework/SafetyAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb900` | `0xbf8c` | **`+0x68c`** |
| `__TEXT.__oslogstring` | `0x2f6c` | `0x326f` | **`+0x303`** |
| `__TEXT.__gcc_except_tab` | `0x11cc` | `0x12b4` | **`+0xe8`** |
| `__TEXT.__cstring` | `0xf54` | `0xfd5` | **`+0x81`** |
| `__AUTH_CONST.__cfstring` | `0xe80` | `0xec0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a0` | `0x5d8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0xc0` | `0xa0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x60` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x6fc` | `0x704` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x540` | `0x548` | **`+0x8`** |

### Other Changes

```diff

-70.0.15.0.0
+70.0.17.0.0

-  Symbols:   489
-  CStrings:  287
+  Symbols:   493
+  CStrings:  299
Symbols:
+ -[SafetyAlerts onUserTappedWithUid:action:]
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _container_system_group_path_for_identifier
+ _xpc_dictionary_set_int64
- ___60-[SafetyAlerts onAPSDConnectionChangeIsOverWiFi:isOverCell:]_block_invoke
CStrings:
+ "apsd_biome_collection.plist"
+ "mapletLoadingStatus"
+ "saUserTappedAction"
+ "shouldCollect"
+ "systemgroup.com.apple.safetyalerts"
+ "userTappedActionType"
+ "userTappedAlertUid"
+ "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange\", \"file\":%{private, location:escape_only}s, \"isAPSDOverWiFi\":%{private}hhd, \"isAPSDOverCell\":%{private}hhd}"
+ "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,#warning,group container not available,not collecting\"}"
+ "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,#warning,plist parse failed,not collecting\", \"file\":%{private, location:escape_only}s, \"error\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,no flag file,not collecting\", \"file\":%{private, location:escape_only}s, \"error\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,not collecting\", \"file\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#saClient,onUserTapped\", \"uid\":%{private, location:escape_only}s, \"action\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#saClient,onUserTapped,cantCreateMessage\"}"
+ "{\"msg%{public}.0s\":\"#saClient,onUserTapped,emptyUid\"}"
+ "{\"msg%{public}.0s\":\"#saClient,onUserTapped,unsupportedPlatform\"}"
- "APSDBiomeCollectionEnabled"
- "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange\", \"isAPSDOverWiFi\":%{private}hhd, \"isAPSDOverCell\":%{private}hhd}"
- "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,not collecting\"}"
- "{\"msg%{public}.0s\":\"#saClient,onAPSDConnectionChange,sandbox\"}"
```
