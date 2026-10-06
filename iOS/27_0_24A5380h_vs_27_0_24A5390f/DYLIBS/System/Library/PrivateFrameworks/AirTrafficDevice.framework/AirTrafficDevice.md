## AirTrafficDevice

> `/System/Library/PrivateFrameworks/AirTrafficDevice.framework/AirTrafficDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f161c` | `0x1f1934` | **`+0x318`** |
| `__TEXT.__oslogstring` | `0x7177` | `0x7260` | **`+0xe9`** |
| `__TEXT.__cstring` | `0x2aee` | `0x2b36` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x2e00` | `0x2e40` | **`+0x40`** |
| `__DATA.__bss` | `0xf8` | `0x138` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0xb0` | `0x70` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x37b0` | `0x37d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x29c8` | `0x29e0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x6248` | `0x6258` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x880` | `0x888` | **`+0x8`** |

### Other Changes

```diff

-4026.100.74.0.0
+4026.110.81.1.0

-  Symbols:   3035
-  CStrings:  982
+  Symbols:   3037
+  CStrings:  986
Symbols:
+ _NSDebugDescriptionErrorKey
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ATSyncClient
Functions:
~ -[ATDeviceSyncManager _initiateSyncForDataClass:onMessageLink:] : 1208 -> 1348
~ ___63-[ATDeviceSyncManager _initiateSyncForDataClass:onMessageLink:]_block_invoke : 680 -> 756
~ -[ATDeviceSyncManager _handleBeginSyncSessionRequest:onMessageLink:] : 1312 -> 1888
CStrings:
+ "%{public}@: Handling request to begin sync session for data class '%{public}@'. params = %{public}@"
+ "%{public}@: Not starting sync for dataclass '%{public}@' because the number of incoming changes exceeds the current limit. (%u > %u)"
+ "Number of pending changes exceeds the current limit"
+ "_PendingChangeCount"
```
