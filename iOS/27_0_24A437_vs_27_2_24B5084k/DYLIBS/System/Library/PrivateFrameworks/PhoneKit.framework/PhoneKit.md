## PhoneKit

> `/System/Library/PrivateFrameworks/PhoneKit.framework/PhoneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19f40` | `0x1a4c4` | **`+0x584`** |
| `__TEXT.__oslogstring` | `0xf23` | `0x1043` | **`+0x120`** |
| `__AUTH_CONST.__objc_const` | `0x1778` | `0x17d8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x9b3` | `0x9e3` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xce0` | `0xd00` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x110c` | `0x112c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x11f0` | `0x1208` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x6c0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x680` | `0x688` | **`+0x8`** |

### Other Changes

```diff

-153.100.1.2.29
+156.200.70.2.2

-  Functions: 530
-  Symbols:   1060
-  CStrings:  191
+  Functions: 535
+  Symbols:   1065
+  CStrings:  195
Symbols:
+ -[PKRecentsController contactsFetchQueue]
+ -[PKRecentsController contactsUpdateGeneration]
+ -[PKRecentsController setContactsUpdateGeneration:]
+ GCC_except_table135
+ _OBJC_IVAR_$_PKRecentsController._contactsFetchQueue
+ _OBJC_IVAR_$_PKRecentsController._contactsUpdateGeneration
+ ___44-[PKRecentsController handleUpdatedContacts]_block_invoke_2
- GCC_except_table133
- _objc_retain_x28
CStrings:
+ "[handleUpdatedContacts] Discarding stale contact fetch (generation %@, current %@)"
+ "[handleUpdatedContacts] Fetching contacts for %lu handles using contact store %@"
+ "[handleUpdatedContacts] Found %lu contacts for contact handle %{sensitive}@; caching the first contact %{sensitive}@"
+ "com.apple.calls.queue.%@.contactsFetch.%p"
```
