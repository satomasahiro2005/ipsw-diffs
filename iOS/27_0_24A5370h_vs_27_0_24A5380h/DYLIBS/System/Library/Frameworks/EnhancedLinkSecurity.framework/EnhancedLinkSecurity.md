## EnhancedLinkSecurity

> `/System/Library/Frameworks/EnhancedLinkSecurity.framework/EnhancedLinkSecurity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ef8` | `0x1e00` | **`-0x30f8`** |
| `__AUTH_CONST.__objc_const` | `0x9e8` | `0x78` | **`-0x970`** |
| `__TEXT.__const` | `0x308` | `0xc2` | **`-0x246`** |
| `__AUTH.__data` | `0x1d0` | `—` | **`-0x1d0`** |
| `__TEXT.__oslogstring` | `0x1c0` | `—` | **`-0x1c0`** |
| `__DATA.__data` | `0x1c0` | `0x10` | **`-0x1b0`** |
| `__TEXT.__constg_swiftt` | `0x180` | `—` | **`-0x180`** |
| `__AUTH_CONST.__auth_got` | `0x348` | `0x1d0` | **`-0x178`** |
| `__AUTH_CONST.__const` | `0x2d8` | `0x168` | **`-0x170`** |
| `__TEXT.__objc_methlist` | `0x19c` | `0x74` | **`-0x128`** |
| `__TEXT.__swift5_typeref` | `0x1bb` | `0x93` | **`-0x128`** |
| `__TEXT.__cstring` | `0xfc` | `—` | **`-0xfc`** |
| `__TEXT.__unwind_info` | `0x230` | `0x138` | **`-0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x140` | `0x60` | **`-0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x80` | `—` | **`-0x80`** |
| `__DATA_CONST.__got` | `0x88` | `0x20` | **`-0x68`** |
| `__TEXT.__eh_frame` | `0x230` | `0x1c8` | **`-0x68`** |
| `__TEXT.__swift5_reflstr` | `0x38` | `—` | **`-0x38`** |
| `__DATA_DIRTY.__data` | `0x58` | `0x28` | **`-0x30`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `—` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x8` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `—` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x90` | `0x84` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0xc` | `—` | **`-0xc`** |
| `__DATA.__bss` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x18` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x18` | **`+0x4`** |

### Other Changes

```diff

-1483.100.10.2.4
-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
+1486.100.5.2.1

-  - /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
+  - /System/Library/Frameworks/LinkSecurity.framework/LinkSecurity

-  Functions: 143
-  Symbols:   101
-  CStrings:  16
+  Functions: 58
+  Symbols:   64
+  CStrings:  0
Symbols:
+ _OBJC_CLASS_$_LSLinkSecurityManager
+ _dispatch_group_create
+ _dispatch_group_enter
+ _dispatch_group_leave
+ _objc_retain_x22
+ _swift_retain_x19
- _IMGetDomainBoolForKey
- _IMGetDomainValueForKey
- _IMSetDomainBoolForKey
- _IMSetDomainValueForKey
- _OBJC_CLASS_$_NSArray
- _OBJC_CLASS_$_NSSet
- _OBJC_CLASS_$_NSURL
- _OBJC_CLASS_$_NSXPCConnection
- _OBJC_CLASS_$_NSXPCInterface
- _OBJC_CLASS_$_OS_dispatch_queue
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- __os_log_impl
- __swiftEmptyArrayStorage
- __swiftEmptySetSingleton
- __swift_stdlib_bridgeErrorToNSError
- _malloc_size
- _objc_release_x21
- _objc_release_x26
- _os_log_type_enabled
- _swift_arrayInitWithCopy
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_deallocClassInstance
- _swift_deletedMethodError
- _swift_dynamicCast
- _swift_endAccess
- _swift_errorRelease
- _swift_errorRetain
- _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_getWitnessTable
- _swift_isUniquelyReferenced_nonNull_native
- _swift_lookUpClassMethod
- _swift_release_x20
- _swift_release_x22
- _swift_release_x24
- _swift_release_x27
- _swift_retain_x20
- _swift_slowAlloc
- _swift_slowDealloc
- _swift_weakDestroy
- _swift_weakInit
- _swift_weakLoadStrong
CStrings:
- "Adding %ld URL(s) to the store"
- "Adding URL to the store"
- "Checking if URL is in the store"
- "Checking sentinel value: %{bool}d"
- "Connection interrupted"
- "Connection invalidated"
- "Could not connect with error: %@"
- "EnhancedLinkSecurityManager"
- "EnhancedLinkSecuritySentinelKey"
- "No URLs were for a website, not adding any to the store"
- "Starting connection to EnhancedLinkSecurityStore"
- "URL was not for a website, not adding to the store"
- "com.apple.Messages"
- "com.apple.Messages.EnhancedLinkSecurityStoreConnection.queue"
- "com.apple.imagent.EnhancedLinkSecurityStore"
- "com.apple.messages.EnhancedLinkSecurity"
```
