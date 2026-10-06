## LocationAuthorizationFramework

> `/System/Library/PrivateFrameworks/LocationAuthorizationFramework.framework/LocationAuthorizationFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60ac0` | `0x66648` | **`+0x5b88`** |
| `__AUTH_CONST.__const` | `0x1680` | `0x1968` | **`+0x2e8`** |
| `__DATA.__bss` | `0x3710` | `0x3910` | **`+0x200`** |
| `__TEXT.__const` | `0x2910` | `0x2ae8` | **`+0x1d8`** |
| `__TEXT.__oslogstring` | `0x6e55` | `0x6ff4` | **`+0x19f`** |
| `__AUTH_CONST.__objc_const` | `0x1ab8` | `0x1c50` | **`+0x198`** |
| `__TEXT.__swift5_reflstr` | `0x4c6` | `0x645` | **`+0x17f`** |
| `__TEXT.__cstring` | `0x27b0` | `0x2891` | **`+0xe1`** |
| `__TEXT.__unwind_info` | `0x1580` | `0x1650` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x11f8` | `0x12b8` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x7b8` | `0x878` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x162c` | `0x16dc` | **`+0xb0`** |
| `__DATA_DIRTY.__bss` | `0x770` | `0x800` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x9dc` | `0xa58` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x1460` | `0x14c0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xe28` | `0xe88` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x3b0` | `0x400` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xb48` | `0xb97` | **`+0x4f`** |
| `__TEXT.__gcc_except_tab` | `0xfd8` | `0x101c` | **`+0x44`** |
| `__AUTH_CONST.__auth_got` | `0xce8` | `0xd28` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x828` | `0x860` | **`+0x38`** |
| `__DATA.__data` | `0x948` | `0x978` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0xa8` | `0xd8` | **`+0x30`** |
| `__DATA_DIRTY.__objc_data` | `0x7d0` | `0x7f8` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x2b4` | `0x2a0` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x9c` | `0xa8` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x8c` | `0x94` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-3164.0.0.0.0
+3169.4.0.0.0

-  Functions: 1823
-  Symbols:   432
-  CStrings:  546
+  Functions: 1912
+  Symbols:   437
+  CStrings:  555
Symbols:
+ _OBJC_CLASS_$_CLSyncableKey
+ _OBJC_METACLASS_$_CLSyncableKey
+ _SetSharedAuthorizationDatabaseForTesting
+ _swift_retain_x28
+ _swift_willThrowTypedImpl
CStrings:
+ "\n               "
+ "%s incoming syncState has no #diff from:%ld to:%ld"
+ "%s new client setup %s %s"
+ "%s no #diff so not sending any changes"
+ "%s settings have changed policy=%{bool}d enabled-edge=%{bool}d %s"
+ "%s shelved excluded capability %ld for %s -> (localValue=%@) (remote=%d)"
+ "%s skipping refresh since the given pdrDevice returned a nil path %@"
+ "/Developer/Library/LocationBundles"
+ "/System/Library/PrivateFrameworks/ManagedDevice.framework"
+ "AuthDB.holdOSTransactionUntilNextPersist"
+ "CapabilityEnabled"
+ "IgnoredCapabilities"
+ "System service found which should not exist"
+ "System service not found on disk"
+ "{\n%s %s local vs remote\nfromPeerIdx:%ld\ntoPeerIdx:%ld\nlocalCapabilities: %s\nremoteCapabilities: %s\nhaveCapabilitiesChanged: %{bool}d\nlocalUnknownCapabilities: %s\nremoteUnknownCapabilities: %s\nlocalTombstones: %s\nremoteTombstones: %s\nlocalIgnoredCapabilities: %s\nlocalVV: %s\nremoteVV: %s\n}"
+ "{\n%s %s resulting state\ncapabilities: %s\nlocalVV:%s\nlocalTombstones:%s\nlocalIgnoredCapabilities:%s\n}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase holdOSTransactionUntilNextPersist\"}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase releasePersistTransaction\"}"
+ "{\"msg%{public}.0s\":\"System service found which should not exist\", \"SystemService\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"System service not found on disk\", \"SystemService\":%{public, location:escape_only}@}"
- "%s adding diff'd client to send to peer %s"
- "%s computed mask from diff buckets: %s"
- "%s incoming syncState has no diff from:%ld to:%ld"
- "%s no #diff needed from:%ld to:%ld, so not sending any changes"
- "%s no diff for incoming digest"
- "%s on peer leaving, determined client %s has consensus to be removed %s"
- "%s remote didn't have a kv store for %s, but this client is locally tombstone'd - deleting client now"
- "%s setting up new client %s %s"
- "%s settings have changed %s"
- "{\n%s %s local vs remote\nfromPeerIdx:%ld\ntoPeerIdx:%ld\nlocalCapabilities: %s\nremoteCapabilities: %s\nlocalUnknownCapabilities: %s\nremoteUnknownCapabilities: %s\nlocalTombstones: %s\nremoteTombstones: %s\nlocalVV: %s\nremoteVV: %s\n}"
- "{\n%s %s resulting state\ncapabilities: %s\nlocalVV:%s\nlocalTombstones:%s\n}"
```
