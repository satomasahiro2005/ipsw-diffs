## Contacts

> `/System/Library/Frameworks/Contacts.framework/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x6358` | `0x6df8` | **`+0xaa0`** |
| `__DATA_DIRTY.__objc_data` | `0x5e10` | `0x5370` | **`-0xaa0`** |
| `__TEXT.__text` | `0x2206d0` | `0x22096c` | **`+0x29c`** |
| `__DATA_CONST.__got` | `0x1d48` | `0x1db0` | **`+0x68`** |
| `__DATA_DIRTY.__bss` | `0xbc8` | `0xbf8` | **`+0x30`** |
| `__TEXT.__cstring` | `0xcbc9` | `0xcbf9` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1bde8` | `0x1be18` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x91d1` | `0x91f1` | **`+0x20`** |
| `__DATA.__bss` | `0x65d0` | `0x65b0` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d08` | `0x9d28` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x91e8` | `0x9208` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2db60` | `0x2db70` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1df0` | `0x1de8` | **`-0x8`** |

### Other Changes

```diff

-3835.100.6.0.0
+3837.100.1.0.0

-  Functions: 14203
-  Symbols:   20146
-  CStrings:  3445
+  Functions: 14213
+  Symbols:   20154
+  CStrings:  3446
Symbols:
+ +[CNAppleAccountAvatarUpdateHelper _drainUpdateQueueWithTimeoutForTesting:]
+ +[CNAppleAccountAvatarUpdateHelper updateQueue]
+ -[CNXPCContactsSupportTestDouble _waitForAvatarUpdatesForTesting]
+ ___47+[CNAppleAccountAvatarUpdateHelper updateQueue]_block_invoke
+ ___75+[CNAppleAccountAvatarUpdateHelper _drainUpdateQueueWithTimeoutForTesting:]_block_invoke
+ ___89+[CNAppleAccountAvatarUpdateHelper updateAppleAccountAvatarForAccount:contactIdentifier:]_block_invoke_2
+ _dispatch_queue_attr_make_with_autorelease_frequency
+ _updateQueue.once
+ _updateQueue.queue
- _swift_getEnumCaseMultiPayload
CStrings:
+ "com.apple.contacts.apple-account-avatar-update"
```
