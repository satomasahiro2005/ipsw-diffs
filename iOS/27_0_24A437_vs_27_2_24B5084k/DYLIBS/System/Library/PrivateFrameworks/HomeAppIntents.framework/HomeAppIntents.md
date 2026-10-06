## HomeAppIntents

> `/System/Library/PrivateFrameworks/HomeAppIntents.framework/HomeAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19c0bc` | `0x1a1d50` | **`+0x5c94`** |
| `__TEXT.__oslogstring` | `0x2ab9` | `0x2e01` | **`+0x348`** |
| `__TEXT.__eh_frame` | `0x7df0` | `0x7f00` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x6258` | `0x6328` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0xcc1e` | `0xcc97` | **`+0x79`** |
| `__TEXT.__const` | `0x22a20` | `0x229c4` | **`-0x5c`** |
| `__TEXT.__cstring` | `0x3c25` | `0x3be5` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2ba1` | `0x2b78` | **`-0x29`** |
| `__TEXT.__swift_as_cont` | `0x674` | `0x69c` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x588` | `0x5a4` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x19e0` | `0x19f8` | **`+0x18`** |
| `__DATA.__data` | `0x7158` | `0x7168` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1180` | `0x1188` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x664` | `0x66c` | **`+0x8`** |

### Other Changes

```diff

-1241.1.7.1.3
+1263.1.0.1.2

-  Functions: 8751
-  Symbols:   4367
-  CStrings:  705
+  Functions: 8774
+  Symbols:   4370
+  CStrings:  713
Symbols:
+ ___swift_exist.box.addr_destructor.2Tm
+ ___swift_exist.box.addr_destructor.68Tm
+ _swift_task_future_wait_throwing
+ _symbolic _____Sg18optimisticSnapshot_ScTyAB______pG14completionTaskt 13HomeDataModel13StateSnapshotV s5ErrorP
+ _symbolic _____Sg18optimisticSnapshot_ScTyAB______pG14completionTasktSg 13HomeDataModel13StateSnapshotV s5ErrorP
+ _type_layout_string 14HomeAppIntents24DeltaAttributeValueEventV
- ___swift_exist.box.addr_destructor.44Tm
- ___swift_exist.box.addr_destructor.8Tm
- _type_layout_string 14HomeAppIntents25GetSetAttributeValueEventV
CStrings:
+ "AppIntentCommandDispatcher.sendWriteCommand: throwing deviceNotFound - deviceAttributeMapper.isEmpty: %{bool}d attributeKinds.isEmpty: %{bool}d devices: %s"
+ "Composing title by joining title tokens"
+ "Composing title from room + device"
+ "Composing title from zone + device"
+ "Composing title from zone + room + device"
+ "DeviceResult.performHAPBlock: HAP read/write threw %@ for devices %s - falling back to the cached snapshot to infer the outcome"
+ "DeviceResult.performProfileBlock: profile read/write threw non-ProfileError %@ for devices %s - dropping it with no fallback snapshot"
+ "Generated title tokens: %{private}s, device: %{private}s, token count: %{public}ld"
+ "No title tokens resolved, composing title from the device alone"
+ "Show Device Result Intent perform() called - successDeviceIDs: %s failedDeviceIDs: %s failedDeviceIDsToIgnore: %s userSpecificity: %s secondaryAccessoryControlDestination: %s destination: %{public}s attributeType: %{public}s source: %{public}s"
- "Generated title tokens: %s"
- "Show Device Result Intent perform() called - successDeviceIDs: %s failedDeviceIDs: %s failedDeviceIDsToIgnore: %s userSpecificity: %s secondaryAccessoryControlDestination: %s"
```
