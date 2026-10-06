## transparencyd

> `/usr/libexec/transparencyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35585c` | `0x356244` | **`+0x9e8`** |
| `__DATA.__bss` | `0x1b6f0` | `0x1b870` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x1517a` | `0x152ca` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0xed40` | `0xee60` | **`+0x120`** |
| `__TEXT.__cstring` | `0x15130` | `0x151f0` | **`+0xc0`** |
| `__TEXT.__const` | `0x23ff8` | `0x240a8` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x1f250` | `0x1f2d8` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x5054` | `0x50bc` | **`+0x68`** |
| `__TEXT.__objc_methname` | `0x26c52` | `0x26c92` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xc1a0` | `0xc1d0` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x1ea00` | `0x1ea20` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5104` | `0x5120` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x910` | `0x928` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x168` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x8d18` | `0x8d28` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x16e8` | `0x16d8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x49f0` | `0x49e0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x16300` | `0x16310` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x8a31` | `0x8a41` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x316e` | `0x317e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd678` | `0xd688` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4430` | `0x443e` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0xd14` | `0xd20` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x2508` | `0x2500` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x444` | `0x448` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1766.40.50.0.0
+1766.40.56.0.0

-  Functions: 20629
-  Symbols:   2278
-  CStrings:  12085
+  Functions: 20639
+  Symbols:   2277
+  CStrings:  12101
Symbols:
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _swift_conformsToProtocol2
CStrings:
+ "StaticKeyOrphanGCEvent"
+ "StaticKeyOrphanGCReaped"
+ "anyHandleStillMatchesAContact:moc:"
+ "changeOptInState: IDS account showed up while waiting for Ready, going on"
+ "changeOptInState: timed out waiting for Ready, account status may be stale"
+ "examined"
+ "garbageCollectOrphanedStaticKeys abandoning pass: all %lu pins resolved as not-found"
+ "garbageCollectOrphanedStaticKeys keeping %@: identifier unresolvable but a handle still matches a contact"
+ "ktDutyCycleGateAttemptFloor"
+ "ktDutyCycleGateRun"
+ "ktDutyCycleGateSuccessFloor"
+ "ktRunDutyCycleFallback"
+ "ktRunDutyCycleForced"
+ "ktRunDutyCycleScheduled"
+ "rpcReasonEventNamesForRequest:"
+ "runDutyCycleInternal:trigger:"
+ "v32@0:8@?16Q24"
- "runDutyCycleInternal:"
```
