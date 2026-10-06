## Email

> `/System/Library/PrivateFrameworks/Email.framework/Email`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd88b0` | `0xd91bc` | **`+0x90c`** |
| `__AUTH_CONST.__objc_const` | `0x169e8` | `0x16b90` | **`+0x1a8`** |
| `__TEXT.__gcc_except_tab` | `0x1ac7c` | `0x1ad70` | **`+0xf4`** |
| `__TEXT.__objc_methlist` | `0xcd6c` | `0xce24` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x8080` | `0x8128` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x200` | `0x250` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6108` | `0x6158` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0xc34` | `0xc44` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x67e3` | `0x67f3` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xbc8` | `0xbd0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xc50` | `0xc58` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x578` | `0x580` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x470` | `0x478` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 5140
-  Symbols:   8897
+  Functions: 5157
+  Symbols:   8927
Symbols:
+ +[EMMessageBodyParsingUtils strippedQuoteBlockFromHTMLBody:]
+ -[EMAccountRepository accountIfAvailableForIdentifier:]
+ -[EMMailboxRepository _cachedAllMailboxObjectIDs]
+ -[EMMailboxRepository _cachedMailboxObjectIDsForMailboxType:]
+ -[EMMailboxRepository _cachedMailboxTypeForMailboxObjectID:cacheValid:]
+ -[EMMailboxRepository _failMailboxesPromiseAsTemporarilyUnavailable]
+ -[EMMailboxRepository availableMailboxTypeResolver]
+ -[EMMailboxRepository isMailboxCacheWarm]
+ -[EMMailboxRepository mailboxesFuture]
+ -[_EMAvailableMailboxTypeResolver .cxx_destruct]
+ -[_EMAvailableMailboxTypeResolver allMailboxObjectIDs]
+ -[_EMAvailableMailboxTypeResolver initWithRepository:]
+ -[_EMAvailableMailboxTypeResolver mailboxObjectIDsForMailboxType:]
+ -[_EMAvailableMailboxTypeResolver mailboxTypeForMailboxObjectID:]
+ _OBJC_CLASS_$__EMAvailableMailboxTypeResolver
+ _OBJC_IVAR_$_EMAccountRepository._accountsRequestInFlight
+ _OBJC_IVAR_$_EMMailbox._repository
+ _OBJC_IVAR_$_EMMailboxRepository._availableMailboxTypeResolver
+ _OBJC_IVAR_$__EMAvailableMailboxTypeResolver._repository
+ _OBJC_METACLASS_$__EMAvailableMailboxTypeResolver
+ __OBJC_$_INSTANCE_METHODS__EMAvailableMailboxTypeResolver
+ __OBJC_$_INSTANCE_VARIABLES__EMAvailableMailboxTypeResolver
+ __OBJC_$_PROP_LIST__EMAvailableMailboxTypeResolver
+ __OBJC_CLASS_PROTOCOLS_$__EMAvailableMailboxTypeResolver
+ __OBJC_CLASS_RO_$__EMAvailableMailboxTypeResolver
+ __OBJC_METACLASS_RO_$__EMAvailableMailboxTypeResolver
+ ___55-[EMAccountRepository accountIfAvailableForIdentifier:]_block_invoke
+ ___61-[EMMailboxRepository _cachedMailboxObjectIDsForMailboxType:]_block_invoke
+ ___remoteInterfaceForConnection_block_invoke
+ _os_unfair_lock_trylock
+ _remoteInterfaceForConnection
- ___54-[EMMailboxRepository mailboxObjectIDsForMailboxType:]_block_invoke
CStrings:
+ "A1"
+ "Error establishing xpc connection: %{public}@"
- "A"
- "Error establishing xpc connection : %@"
```
