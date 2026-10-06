## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76bcc` | `0x77470` | **`+0x8a4`** |
| `__TEXT.__oslogstring` | `0x7ed8` | `0x7fa8` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x21a8` | `0x2168` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x157c` | `0x15a0` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0xbf8` | `0xbd8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xbb14` | `0xbb2c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x698` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x14170` | `0x14178` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d90` | `0x3d98` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-449.30.6.14.8
+449.30.6.14.15

-  Functions: 4390
-  Symbols:   7318
-  CStrings:  1570
+  Functions: 4392
+  Symbols:   7320
+  CStrings:  1572
Symbols:
+ -[SPIntentSession redonateItemEntitiesWithCompletion:]
+ ___block_descriptor_56_e8_32s40bs48w_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16lw48l8s32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16lw56l8s32l8s48l8s40l8
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _kBeaconUpdateQueueKey
- ___block_descriptor_32_e20_v20?0B8"NSError"12l
- ___block_descriptor_48_e8_32bs40w_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16lw40l8s32l8
- ___block_descriptor_48_e8_32s40s_e20_v20?0B8"NSError"12ls32l8s40l8
- ___block_descriptor_56_e8_32s40bs48w_e51_v24?0"NSOrderedCollectionDifference"8"NSError"16lw48l8s40l8s32l8
CStrings:
+ "SPInternalSimpleBeacon: decoded nil for nonnull `identifier`; substituting all-zero UUID. Beacon will not match any client filter and is dropped downstream."
+ "SPInternalSimpleBeacon: decoded nil for nonnull `productUUID`; substituting all-zero UUID."
+ "[%{public}@] Error during update for %@: %@"
+ "[%{public}@] Error during update: %@"
+ "[%{public}@] Error stopping session. stopped=%i error: %@"
+ "[%{public}@] Failed to start session. subscribed=%i error: %@"
+ "[%{public}@] Session started"
+ "[%{public}@] self deallocated before update fired"
+ "com.apple.icloud.searchpartyd.simpleBeaconUpdate"
- "Error during update of device %@ error: %@"
- "Error during update of devices error: %@"
- "Error stopping fetch of device for %@. Stopped %i, error: %@"
- "Error stopping fetch of devices. Stopped %i, error: %@"
- "Starting fetch of device for %@. Subscribed %i, error: %@"
- "Starting fetch of devices. Subscribed %i, error: %@"
- "com.apple.icloud.seachpartyd.simpleBeaconUpdate"
```
