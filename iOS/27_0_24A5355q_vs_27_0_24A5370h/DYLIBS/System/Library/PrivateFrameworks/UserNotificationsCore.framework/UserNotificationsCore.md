## UserNotificationsCore

> `/System/Library/PrivateFrameworks/UserNotificationsCore.framework/UserNotificationsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22f59c` | `0x231960` | **`+0x23c4`** |
| `__DATA.__bss` | `0xf520` | `0xfba0` | **`+0x680`** |
| `__TEXT.__const` | `0x13468` | `0x13788` | **`+0x320`** |
| `__TEXT.__unwind_info` | `0x63d8` | `0x64d8` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0xda50` | `0xdb08` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x5114` | `0x51b0` | **`+0x9c`** |
| `__AUTH.__data` | `0x3710` | `0x37a0` | **`+0x90`** |
| `__DATA.__data` | `0x4458` | `0x44e8` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x11567` | `0x115f7` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x8248` | `0x82b8` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x7910` | `0x797c` | **`+0x6c`** |
| `__TEXT.__swift5_typeref` | `0x77ea` | `0x7848` | **`+0x5e`** |
| `__TEXT.__swift5_proto` | `0xd50` | `0xd84` | **`+0x34`** |
| `__TEXT.__swift5_assocty` | `0x6f0` | `0x720` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x4737` | `0x4767` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x1f4` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2300` | `0x2310` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3df8` | `0x3e08` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x5d8` | `0x5e4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1720` | `0x1728` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5f5c` | `0x5f64` | **`+0x8`** |

### Other Changes

```diff

-703.0.0.0.0
+708.0.0.0.0

-  Functions: 9457
-  Symbols:   6439
-  CStrings:  2196
+  Functions: 9489
+  Symbols:   6452
+  CStrings:  2197
Symbols:
+ +[UNCNotificationSourceDescription(Factory) ephemeralAppClipSourceDescriptionWithBundleIdentifier:]
+ _OBJC_CLASS_$_BSBuildVersion
+ _associated conformance 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysOSHAASQ
+ _associated conformance 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysOs0P3KeyAAs23CustomStringConvertible
+ _associated conformance 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysOs0P3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So23NSURLFileProtectionTypeaSHSCSQ
+ _associated conformance So23NSURLFileProtectionTypeas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So23NSURLFileProtectionTypeas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic _____ 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV
+ _symbolic _____ 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysO
+ _symbolic _____ So23NSURLFileProtectionTypea
+ _symbolic _____y_____G s22KeyedDecodingContainerV 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 21UserNotificationsCore31AppleWatchForwardingRecordStore33_C9A03BC249DD699D896BC7E941311696LLV10CodingKeysO
CStrings:
+ "Loaded versioned store (v%{public}ld, build %{public}s, written %{public}s)"
+ "Removing unreadable watch forwarding configuration written by a prior release"
+ "Removing watch forwarding configuration written by a prior release, file protection is %s"
+ "Writing %{public}ld Apple Watch forwarding records (v%{public}ld, build %{public}s) to %{public}s"
- "Failed to update data protection class for watch forwarding configuration: %@"
- "Updating data protection class for watch forwarding configuration"
- "Writing %ld Apple Watch forwarding records to %s"
```
