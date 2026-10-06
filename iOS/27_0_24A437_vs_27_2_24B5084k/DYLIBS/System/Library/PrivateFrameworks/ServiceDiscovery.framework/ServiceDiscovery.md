## ServiceDiscovery

> `/System/Library/PrivateFrameworks/ServiceDiscovery.framework/ServiceDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a2104` | `0x1a4448` | **`+0x2344`** |
| `__TEXT.__eh_frame` | `0xcf44` | `0xd04c` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x4708` | `0x4788` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2a65` | `0x2ad5` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x6c66` | `0x6c16` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x5980` | `0x59c8` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0xa70` | `0xab0` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x594` | `0x5ac` | **`+0x18`** |
| `__DATA.__data` | `0x1908` | `0x1918` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3188` | `0x3178` | **`-0x10`** |
| `__TEXT.__const` | `0xa94c` | `0xa95c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x336b` | `0x335b` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x518` | `0x524` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x928` | `0x930` | **`+0x8`** |

### Other Changes

```diff

-751.100.2.0.0
+751.200.31.0.0

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 4926
-  Symbols:   1758
-  CStrings:  881
+  Functions: 4954
+  Symbols:   1760
+  CStrings:  882
Symbols:
+ ___swift_closure_destructor.36Tm
+ ___swift_closure_destructor.48Tm
+ ___swift_closure_destructor.94Tm
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_ServiceDiscovery
- ___swift_closure_destructor.35Tm
- ___swift_closure_destructor.74Tm
- _symbolic ______p 16ServiceDiscovery22PersonaMonitorDelegateP
CStrings:
+ "Fetching personas"
+ "com.apple.nearbysharingd.NearbySharing"
+ "com.apple.network.ServiceDiscovery.personaObservation"
- "Refreshing Personas to determine effective value for %s"
- "Refreshing Personas to prepare for enumeration"
```
