## locationd

> `/usr/libexec/locationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b280ac` | `0x1b29030` | **`+0xf84`** |
| `__TEXT.__oslogstring` | `0x291f05` | `0x2924c5` | **`+0x5c0`** |
| `__TEXT.__cstring` | `0x210541` | `0x210791` | **`+0x250`** |
| `__TEXT.__objc_stubs` | `0x3e420` | `0x3e4c0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xc1c08` | `0xc1ba8` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0xda4d0` | `0xda518` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x77868` | `0x778a0` | **`+0x38`** |
| `__TEXT.__const` | `0x166848` | `0x166878` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2e6d0` | `0x2e700` | **`+0x30`** |
| `__DATA.__objc_const` | `0x4f690` | `0x4f670` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x13b78` | `0x13b98` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x5d07f` | `0x5d09f` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x39047` | `0x39037` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3bf8` | `0x3bf4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3186.0.12.0.0
+3186.0.17.0.1

-  Functions: 114069
+  Functions: 114089

-  CStrings:  85192
+  CStrings:  85219
CStrings:
+ "-[CMDeviceStateManager simulateDeviceStateEventForPropertyA:propertyA0:propertyA1:propertyB:propertyC:propertyD:delaySecs:]"
+ "-[CMDeviceStateManagerInternal feedDeviceStateEvent:propertyA0Type:propertyA1Type:propertyBType:propertyCType:propertyDType:timestamp:continuousTimestamp:timestampAPArrivalSecs:]"
+ "-[CMDeviceStateManagerInternal sendEventToClientPrivate]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocation/Framework/CoreMotion/DeviceState/CMDeviceStateManager.mm"
+ "22:38:03"
+ "22:45:38"
+ "Dropping event after teardown in onDeviceStateData:."
+ "First PedNet steps received from AOP2, holding mode,%d,due to active override"
+ "GPSODOM,dropping stale accumulation,gnssOnly,%{public}.1lf,fAccumulatedDeltaDistanceDifferenceM,%{public}.1lf,baselineOffset,%{public}.1lf"
+ "GPSODOM,gnss-only cumulative distance discarded,gnssOnly,%{public}.1lf,fAccumulatedDeltaDistanceDifferenceM,%{public}.1lf,baselineOffset,%{public}.1lf"
+ "GPSODOM,odometer,%{public}.1lf,fAccumulatedDeltaDistanceDifferenceM,%{public}.1lf,baselineOffset,%{public}.1lf,isFromBufferedGnss,%{public}d"
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
+ "Sep 15 2026 22:41:46"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA0]"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA1]"
+ "[CMDeviceStateEvent isValidPropertyA:propertyA]"
+ "[CMDeviceStateEvent isValidPropertyB:propertyB]"
+ "[CMDeviceStateEvent isValidPropertyC:propertyC]"
+ "[CMDeviceStateEvent isValidPropertyD:propertyD]"
+ "isValidPropertyA:"
+ "isValidPropertyB:"
+ "isValidPropertyBAngle:"
+ "isValidPropertyC:"
+ "isValidPropertyD:"
+ "v72@0:8q16q24q32q40q48q56d64"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA0 value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyA1 value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyB value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyC value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"Invalid simulated propertyD value\", \"event\":%{public, location:escape_only}s, \"condition\":%{private, location:escape_only}s}"
- "-[CMDeviceStateManager feedDeviceStateEvent:propertyA0Type:propertyA1Type:propertyBType:propertyCType:propertyDType:timestamp:continuousTimestamp:timestampAPArrivalSecs:]_block_invoke"
- "-[CMDeviceStateManager sendEventToClientPrivate]"
- "00:12:12"
- "00:21:47"
- "First PedNet steps received from AOP2, staying in LegacyOnly due to active override"
- "GPSODOM,dropping stale accumulation,gnssOnly,%{public}.1lf"
- "GPSODOM,gnss-only cumulative distance discarded,gnssOnly,%{public}.1lf,accumulated,%{public}.1lf,baselineOffset,%{public}.1lf"
- "GPSODOM,odometer,%.1lf,fAccumulatedDeltaDistanceDifferenceM,%.1lf,baselineOffset,%.1lf,isFromBufferedGnss,%d"
- "Sep 11 2026"
- "Sep 11 2026 00:16:37"
- "fNotifyAllClients"
- "simulateDeviceStateEvent:propertyB:propertyC:delaySecs:"
- "v36@0:8C16C20C24d28"
- "v48@0:8C16C20C24C28C32C36d40"
```
