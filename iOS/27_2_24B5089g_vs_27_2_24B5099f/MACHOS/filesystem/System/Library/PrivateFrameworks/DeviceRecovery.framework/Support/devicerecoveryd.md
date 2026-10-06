## devicerecoveryd

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x278a8` | `0x293f4` | **`+0x1b4c`** |
| `__TEXT.__oslogstring` | `0x3b75` | `0x4059` | **`+0x4e4`** |
| `__TEXT.__cstring` | `0x8100` | `0x8510` | **`+0x410`** |
| `__TEXT.__objc_methname` | `0x2b50` | `0x2e00` | **`+0x2b0`** |
| `__TEXT.__objc_stubs` | `0x2920` | `0x2b80` | **`+0x260`** |
| `__DATA_CONST.__cfstring` | `0x3180` | `0x3360` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0xe2c` | `0xf04` | **`+0xd8`** |
| `__DATA.__objc_selrefs` | `0xc70` | `0xd20` | **`+0xb0`** |
| `__DATA.__objc_const` | `0x1750` | `0x17d0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x818` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1300` | `0x1340` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x684` | `0x6b8` | **`+0x34`** |
| `__DATA_CONST.__const` | `0xd58` | `0xd88` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x697` | `0x6be` | **`+0x27`** |
| `__DATA_CONST.__auth_got` | `0x990` | `0x9b0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x258` | `0x278` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-150.40.7.0.0
+150.40.9.0.0

+  - /System/Library/PrivateFrameworks/MobileActivation.framework/MobileActivation

-  Functions: 891
-  Symbols:   402
-  CStrings:  1778
+  Functions: 927
+  Symbols:   410
+  CStrings:  1856
Symbols:
+ _MAECopyActivationRecordWithError
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_NSSet
+ _fsync
+ _kMADeviceConfigurationFlags
+ _objc_setProperty_nonatomic_copy
+ _write
CStrings:
+ "!self.eraseAndUpdateRestricted"
+ "%{public}s: %lu client(s) restricting EACS / Software Update"
+ "%{public}s: %{public}@ in %{public}@ is missing or is not an array - treating the device as unrestricted"
+ "%{public}s: %{public}@ is not a string - leaving the demo device state unchanged"
+ "%{public}s: %{public}s EACS / Software Update restriction for '%{public}@'"
+ "%{public}s: '%{public}@' is already %{public}s"
+ "%{public}s: could not flush %{public}@: %{darwin.errno}d"
+ "%{public}s: could not open %{public}@: %{darwin.errno}d"
+ "%{public}s: could not read %{public}@ - treating the device as unrestricted"
+ "%{public}s: could not read the activation record: %{public}@ - leaving the demo device state unchanged"
+ "%{public}s: could not serialise the restriction clients: %{public}@"
+ "%{public}s: could not stat %{public}@: %{darwin.errno}d"
+ "%{public}s: could not stat the parent of %{public}@: %{darwin.errno}d"
+ "%{public}s: could not write %{public}@: %{darwin.errno}d"
+ "%{public}s: demo device is %{BOOL}d (device configuration flags 0x%lx from %{public}@)"
+ "%{public}s: dropping an unusable client entry in %{public}@"
+ "%{public}s: no %{public}@ - no client has restricted EACS / Software Update"
+ "%{public}s: the update volume is not mounted at %{public}@ - refusing to record a restriction that DRE would not see"
+ ", "
+ "-[DeviceRecoveryService activationRecordWithError:]"
+ "-[DeviceRecoveryService readRestrictionClients]"
+ "-[DeviceRecoveryService restrictionsPathIsOnUpdateVolume]"
+ "-[DeviceRecoveryService setEraseAndUpdateRestriction:forClient:completion:]"
+ "-[DeviceRecoveryService setRestrictionClients:]"
+ "-[DeviceRecoveryService updateDemoDeviceRestriction]"
+ ".."
+ "/private/var/MobileSoftwareUpdate/DeviceRecoveryRestrictions.plist"
+ "22:26:33"
+ "; "
+ "@\"NSSet\""
+ "@24@0:8^@16"
+ "Booting to NeRD is restricted by: %@"
+ "ClientsRestrictingEraseAndUpdate"
+ "Denying client connection - client is missing 'com.apple.DeviceRecovery.Control' entitlement"
+ "EACS is restricted by: %@"
+ "EraseAndUpdateRestricted"
+ "Sep 27 2026"
+ "T@\"NSSet\",C,N,V_cachedRestrictionClients"
+ "TB,N,V_isDemoDevice"
+ "TB,R,N"
+ "[self clientHasRestrictEraseAndUpdateEntitlement:client]"
+ "[self setRestrictionClients:updatedClients]"
+ "_cachedRestrictionClients"
+ "_isDemoDevice"
+ "activationRecordWithError:"
+ "addEraseAndUpdateRestrictionForClient:completion:"
+ "adding"
+ "allObjects"
+ "auto-boot-once"
+ "cachedRestrictionClients"
+ "client %@ missing '%@' entitlement required to restrict EACS / Software Update"
+ "clientHasRestrictEraseAndUpdateEntitlement:"
+ "clientIdentifier.length > 0"
+ "com.apple.DeviceRecovery.RestrictEraseAndUpdate"
+ "compare:"
+ "could not %s restriction for %@"
+ "dataWithPropertyList:format:options:error:"
+ "demo device"
+ "eraseAndUpdateRestricted"
+ "isDemoDevice"
+ "no client identifier provided"
+ "readRestrictionClients"
+ "record"
+ "registered"
+ "remove"
+ "removeEraseAndUpdateRestrictionForClient:completion:"
+ "removeObject:"
+ "removing"
+ "restrictionClients"
+ "restrictionReason"
+ "restrictionsPathIsOnUpdateVolume"
+ "set"
+ "setCachedRestrictionClients:"
+ "setEraseAndUpdateRestriction:forClient:completion:"
+ "setIsDemoDevice:"
+ "setRestrictionClients:"
+ "sortedArrayUsingSelector:"
+ "the system data volume is not mounted"
+ "timed out after %ds reading the activation record"
+ "unregistered"
+ "updateDemoDeviceRestriction"
+ "v36@0:8B16@20@?28"
- "22:57:06"
- "Denying client connection - client does not have 'com.apple.DeviceRecovery.Control' entitlement"
- "Sep 13 2026"
- "auto-boot"
```
