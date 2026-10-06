## FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc54a8` | `0xc5d84` | **`+0x8dc`** |
| `__TEXT.__oslogstring` | `0x5206` | `0x5316` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x10cbd` | `0x10d3d` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0xacc0` | `0xad40` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x40e8` | `0x4138` | **`+0x50`** |
| `__DATA.__objc_const` | `0x9480` | `0x94b0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2e81` | `0x2eb1` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x1fa0` | `0x1fc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2e50` | `0x2e68` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x5c1c` | `0x5c2c` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x35e1` | `0x35f1` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1360` | `0x1370` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3ac` | `0x3b8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x3da0` | `0x3da8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf08` | `0xf10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x31c` | `0x320` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x1bc4` | `0x1bc8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3072.100.1.2.5
+3077.200.51.2.1

-  Functions: 3685
-  Symbols:   1497
-  CStrings:  3769
+  Functions: 3692
+  Symbols:   1498
+  CStrings:  3777
Symbols:
+ _OBJC_CLASS_$_NSUUID
CStrings:
+ "@\"NSUUID\""
+ "T@\"NSObject<OS_dispatch_queue>\",R,N,V_contactsFetchQueue"
+ "T@\"NSUUID\",&,N,V_contactsUpdateGeneration"
+ "[handleUpdatedContacts] Discarding stale contact fetch (generation %@, current %@)"
+ "[handleUpdatedContacts] Fetching contacts for %lu handles using contact store %@"
+ "[handleUpdatedContacts] Found %lu contacts for contact handle %{sensitive}@; caching the first contact %{sensitive}@"
+ "_contactsFetchQueue"
+ "_contactsUpdateGeneration"
+ "com.apple.calls.queue.%@.contactsFetch.%p"
+ "contactsFetchQueue"
+ "contactsUpdateGeneration"
+ "recentCallsWithCompletion:"
+ "setContactsUpdateGeneration:"
- "TB,N,V_screensaverActive"
- "_handleScreenSaverActiveDidChange"
- "_screensaverActive"
- "screensaverActive"
- "setScreensaverActive:"
```
