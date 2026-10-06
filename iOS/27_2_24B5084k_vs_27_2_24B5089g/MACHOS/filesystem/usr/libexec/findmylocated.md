## findmylocated

> `/usr/libexec/findmylocated`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x597f28` | `0x5a2ca4` | **`+0xad7c`** |
| `__TEXT.__eh_frame` | `0x48ea8` | `0x49770` | **`+0x8c8`** |
| `__DATA_CONST.__const` | `0x18268` | `0x18588` | **`+0x320`** |
| `__TEXT.__const` | `0x20378` | `0x20648` | **`+0x2d0`** |
| `__DATA.__data` | `0xeea0` | `0xf080` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x192ec` | `0x194ac` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x15f60` | `0x15dd8` | **`-0x188`** |
| `__TEXT.__cstring` | `0xb9f2` | `0xbb12` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x8fa8` | `0x90ac` | **`+0x104`** |
| `__TEXT.__constg_swiftt` | `0x70a0` | `0x717c` | **`+0xdc`** |
| `__TEXT.__swift5_typeref` | `0x7124` | `0x71fe` | **`+0xda`** |
| `__TEXT.__swift5_reflstr` | `0x7dad` | `0x7e7d` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x4db8` | `0x4e5c` | **`+0xa4`** |
| `__TEXT.__swift_as_cont` | `0x4480` | `0x4508` | **`+0x88`** |
| `__DATA.__bss` | `0x2d880` | `0x2d900` | **`+0x80`** |
| `__TEXT.__swift_as_ret` | `0x2898` | `0x290c` | **`+0x74`** |
| `__DATA.__objc_const` | `0x6358` | `0x6398` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x4ee5` | `0x4f25` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x16e8` | `0x1720` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x1858` | `0x1888` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x5d10` | `0x5d30` | **`+0x20`** |
| `__DATA.__common` | `0x13c0` | `0x13d8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x12c` | `0x140` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x7e4` | `0x7f8` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x2e90` | `0x2ea0` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1780` | `0x1784` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-141.31.6.16.16
+141.31.6.16.17

-  Functions: 17506
-  Symbols:   2827
-  CStrings:  3858
+  Functions: 17653
+  Symbols:   2830
+  CStrings:  3873
Symbols:
+ _$sSL2leoiySbx_xtFZTj
+ _$ss12StaticStringV11descriptionSSvg
+ _$ss12StaticStringVMn
CStrings:
+ "$__lazy_storage_$_cacheExpiryScheduler"
+ "%{public}s expired Friend:%{private,mask.hash}s\nexpiresByGroupId:%{private,mask.hash}s\nlocationSharingState:%{private,mask.hash}s"
+ "%{public}s missing XPC alarm event handler"
+ "%{public}s not eligible, since we have non-nil, non-stale serverSettings already."
+ "%{public}s: No LocalStorageService; skipping donation"
+ "Elapsed: %{public}s"
+ "Expiry alarm fired: %{public}s"
+ "Force refreshClient, since server settings are nil or stale in local DB."
+ "LabelStore: labels changed for %{public}ld users, re-donating Person Entities"
+ "No upcoming expiry; alarm cleared"
+ "Re-arming after %{public}s"
+ "Waking at %{public}s for %{public}s"
+ "_retrieveAndDonatePersonEntities(impactedUsers:)"
+ "com.apple.findmy.findmylocate.ExpiryAlarm"
+ "determineIfAnyUpdatesNeeded(previousMeDevice:previousShareMyLocationState:previousFriendshipRequestsAllowed:)"
+ "expiryAlarmDebounceTask"
+ "registerExpiryAlarmHandler()"
+ "updateLocalStorage(with:)"
- "%{public}s expired Friend:%{private,mask.hash}s\nexpiresByGroupId:%{private,mask.hash}s"
- "%{public}s not eligible, since we have non-nil serverSettings already."
- "Force refreshClient, since we have nil server settings in local DB."
```
