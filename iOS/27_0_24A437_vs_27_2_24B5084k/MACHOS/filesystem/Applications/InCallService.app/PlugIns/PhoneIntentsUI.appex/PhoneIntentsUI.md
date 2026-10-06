## PhoneIntentsUI

> `/Applications/InCallService.app/PlugIns/PhoneIntentsUI.appex/PhoneIntentsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77380` | `0x77a98` | **`+0x718`** |
| `__TEXT.__objc_methname` | `0xfc29` | `0xfd49` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x299f` | `0x2aaf` | **`+0x110`** |
| `__DATA.__objc_const` | `0x7730` | `0x7790` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x9520` | `0x9580` | **`+0x60`** |
| `__TEXT.__cstring` | `0x17f0` | `0x1820` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4bbc` | `0x4bec` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2db0` | `0x2dd8` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3290` | `0x32b0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0xea0` | `0xec0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1fc8` | `0x1fe0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x410` | `0x418` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7f8` | `0x800` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-153.100.1.2.29
+156.200.70.2.2

-  Functions: 2623
-  Symbols:   521
-  CStrings:  3013
+  Functions: 2631
+  Symbols:   522
+  CStrings:  3026
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
```
