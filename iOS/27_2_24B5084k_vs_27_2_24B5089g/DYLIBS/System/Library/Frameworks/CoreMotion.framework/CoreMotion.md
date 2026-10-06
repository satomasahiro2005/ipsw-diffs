## CoreMotion

> `/System/Library/Frameworks/CoreMotion.framework/CoreMotion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x42e0` | `0x320` | **`-0x3fc0`** |
| `__DATA_DIRTY.__objc_data` | `0x15e0` | `0x55a0` | **`+0x3fc0`** |
| `__TEXT.__text` | `0x3cf9f8` | `0x3d0b34` | **`+0x113c`** |
| `__TEXT.__oslogstring` | `0x2f779` | `0x2fcb7` | **`+0x53e`** |
| `__TEXT.__cstring` | `0x477f3` | `0x47a46` | **`+0x253`** |
| `__DATA_CONST.__const` | `0x3d68` | `0x3d20` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0xd964` | `0xd994` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1dd88` | `0x1dd68` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x56f8` | `0x5718` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xd4d0` | `0xd4dc` | **`+0xc`** |
| `__DATA.__data` | `0xe18` | `0xe10` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xbce0` | `0xbcd8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x17bc` | `0x17b8` | **`-0x4`** |

### Other Changes

```diff

-3186.0.12.0.0
+3186.0.17.0.1

-  Functions: 12715
+  Functions: 12717

-  CStrings:  11414
+  CStrings:  11439
CStrings:
+ "-[CMDeviceStateManager simulateDeviceStateEventForPropertyA:propertyA0:propertyA1:propertyB:propertyC:propertyD:delaySecs:]"
+ "-[CMDeviceStateManagerInternal feedDeviceStateEvent:propertyA0Type:propertyA1Type:propertyBType:propertyCType:propertyDType:timestamp:continuousTimestamp:timestampAPArrivalSecs:]"
+ "-[CMDeviceStateManagerInternal sendEventToClientPrivate]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreMotionFramework/Framework/CoreMotion/DeviceState/CMDeviceStateManager.mm"
+ "21:39:32"
+ "Dropping event after teardown in onDeviceStateData:."
+ "Invalid simulated propertyA value"
+ "Invalid simulated propertyA0 value"
+ "Invalid simulated propertyA1 value"
+ "Invalid simulated propertyB value"
+ "Invalid simulated propertyC value"
+ "Invalid simulated propertyD value"
+ "No internal state, ignoring onNotification."
+ "No internal state, skipping teardown."
+ "No internal state; ignoring startUpdatesPrivateToQueue:withHandler:"
+ "No internal state; ignoring startUpdatesToQueue:withHandler:"
+ "Sep 15 2026"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA0]"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA1]"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA]"
+ "[CMDeviceStateEvent isValidPropertyB:propertyB]"
+ "[CMDeviceStateEvent isValidPropertyC:propertyC]"
+ "[CMDeviceStateEvent isValidPropertyD:propertyD]"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA0 value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA1 value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyB value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyC value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyD value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
- "-[CMDeviceStateManager feedDeviceStateEvent:propertyA0Type:propertyA1Type:propertyBType:propertyCType:propertyDType:timestamp:continuousTimestamp:timestampAPArrivalSecs:]_block_invoke"
- "-[CMDeviceStateManager sendEventToClientPrivate]"
- "22:28:36"
- "Sep 10 2026"
```
